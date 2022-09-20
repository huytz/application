# application

# template in local to check yaml

```
helm template cms ./application -f cms.yaml
helm template frontend ./application -f frontend.yaml

```

# install frontend:

```
helm upgrade --install frontend ./application -f frontend.yaml
```


# install backend:

```
helm upgrade --install backend ./application -f backend.yaml
```

# Redeploy applications
```
kubectl rollout restart deploy frontend

kubectl rollout restart deploy cms
```



