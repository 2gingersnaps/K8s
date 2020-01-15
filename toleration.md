# tolerations
```sh
kubectl edit deployment test
# make updates under ...
# deployment.spec.template.spec.tolerations.key
# deployment.spec.template.spec.tolerations.operator
# deployment.spec.template.spec.tolerations.effect
```
> Valid operators:
* “Exists”
* “Equals”

> Valid Effects:
* NoSchedule
* PreferNoSchedule
* NoExecute
