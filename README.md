# k8s-demo

Login:
```shell
gcloud auth login
```

Setup cluster
```shell
gcloud container clusters get-credentials CLUSTER_NAME
```

Deploy (deployment):
```shell
kubectl apply -f src/deployment.yaml
```

Deploy (service)
```shell
kubectl apply -f src/service.yaml
```

List of contexts
````shell
kubectl config get-contexts 
````

Remove context from config (not from server)
```shell
kubectl config delete-context CONTEXT_NAME 
```

Links:
* [gcloud install](https://cloud.google.com/sdk/docs/install)
* [gcloud auth](https://cloud.google.com/sdk/gcloud/reference/auth)
* [configure cluster](https://cloud.google.com/kubernetes-engine/docs/how-to/cluster-access-for-kubectl)
* [expose services](https://cloud.google.com/kubernetes-engine/docs/how-to/exposing-apps)
* [kubectx](https://github.com/ahmetb/kubectx)
* [helm](https://helm.sh/)
