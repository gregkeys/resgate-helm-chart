# resgate-helm-chart


## Getting started with Resgate using Helm

In this repo you can find the Helm 3 based [chart](hhttps://github.com/gregkeys/resgate-helm-chart/) to install Resgate.

```sh
> helm repo add resgate https://github.com/gregkeys/resgate-helm-chart/
> helm repo update

> helm repo list
NAME          	URL 
resgate          	https://github.com/gregkeys/resgate-helm-chart/

> helm install my-resgate resgate/resgate
> helm install my-resgate resgate/resgate --set ingress.enabled=true
```