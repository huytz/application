# application

# install frontend:

```
helm install frontend ./application -f frontend.yaml
```


# install backend:

```
helm install backend ./application -f backend.yaml
```

# Redeploy applications
```
kubectl rollout restart deploy frontend

kubectl rollout restart deploy cms
```



