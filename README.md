# k8s-getting-started
K8s learning notebook

## Proxy

```
kubectl proxy --accept-hosts='^localhost$,^127\.0\.0\.1$,^\[::1\]$,^analytics$' --address='0.0.0.0' --port=3306
```
