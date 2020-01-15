# Schedule Pods on select nodes via Labels and nodeSelectors
```sh
kubectl edit node test
# make updates under node.metadata.labels
# key:value
```
>OR

```sh
kubectl label node-test node_name key=value
```
```sh
kubectl edit deployment test
# make updates under deployment.spec.nodeSelector:
# key:value to match the above node label key:value
```
