# httpenv on k8s

Kubernetes and helm stuff to use the [httpenv](https://hub.docker.com/r/bretfisher/httpenv) app on kubernetes.

## Use

```shell
helm upgrade -i --namespace default httpenv . --version 0.1.0
```