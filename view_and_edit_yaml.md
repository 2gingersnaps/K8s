# Scaffold, view, and edit yaml
## deployment
```sh
kubectl create deployment test --image=busybox -o yaml >> test.yaml
```
```sh
kubectl get deployment test -o yaml >> test.yaml
```
```sh
kubectl edit deployment test
```
```sh
vi test.yaml
```
