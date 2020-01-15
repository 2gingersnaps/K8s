# add a taint
> Blacklist an pod scheduling event on a desired node

> Only 3 effects are possible:
* NoSchedule
* PreferNoSchedule
* NoExecute

```sh
kubectl edit node
# make changes under node.spec.taints
```
```sh
kubectl taint nodes test-node key1=value1:NoSchedule
```

# remove a taint
```sh
kubectl edit node
# make changes under node.spec.taints
```
> Like creating a taint but with "-" at the end of the command

```sh
kubectl taint nodes test-node key1=value1:NoSchedule-
```
```sh
# shorthand version - leave out value
kubectl taint nodes test-node key1=NoSchedule-
```
