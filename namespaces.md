# namespace tips
## Standard namespaces for a basic cluster
> kube-system

> kube-proxy

> default (everything else)
## all namespaces
> add flag

```sh
kubectl get deployment test --all-namespaces
```
## one desired namespace
> In some cases you cannot use --all-namespaces

```sh
kubectl get deployment test -n test-namespace
```
