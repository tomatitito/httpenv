# httpenv on k8s

Kubernetes and helm stuff to use the [httpenv](https://hub.docker.com/r/bretfisher/httpenv) app on kubernetes.

## Install

```shell
helm upgrade -i --namespace default helm . --version 0.1.0
```

## Use

Depending on the service type run

```shell
curl http://<service_ip>:8888
```

locally or from some pod inside the cluster.