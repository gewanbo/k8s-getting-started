# k8s-getting-started
K8s learning notebook

## Start minikube in local country, especially China (Nice option, thanks to all distributors!)
```
minikube start --image-mirror-country='cn'
```

## Proxy Dashboard

```
kubectl proxy --accept-hosts='^localhost$,^127\.0\.0\.1$,^\[::1\]$,^analytics$' --address='0.0.0.0' --port=8800
```

## Forward port to access MySQL
```
kubectl port-forward pod/dev-mysql-86c9454b4b-bffdf 3306:3306
```

