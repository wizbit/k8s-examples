# k8s-examples

## Helloworld

Deploys a helloworld app across up to three clusters, uses Istio's Destination Rule to handle cross cluster routing

```shell
kubectl apply -f helloworld/appset.yaml
```

## Scale To Zero

Deploy whoami app that scales to zero using Keda's HttpAddon.

```shell
kubectl apply -f scale-to-zero/application.yaml
```