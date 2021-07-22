# kubernetes_study
kubernetes入門


### コマンド

- kubernetes が管理するオブジェクトを確認
```
kubectl get all
```

- pod一覧を確認
```
kubectl get pod
```
- Podからログを表示
```
kubectl logs -f [Pod名]
```

- pod削除
```
kubectl delete pod [Pod名]
```

- クラスタのノード一覧表示
```
kubectl get nodes
```
- クラスタのノード詳細情報表示
```
kubectl describe nodes
```

- “Watch” で常に表示
```
watch -t 'kubectl get pod'
```