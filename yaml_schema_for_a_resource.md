# Look up the yaml schema for a resource
## Drill down one level at a time via cli
```sh
kubectl explain deployment
kubectl explain deployment.metadata
kubectl explain deployment.metadata.name
# ...
```
