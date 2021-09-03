# microk8s-poc
Kubernetes PoC using microk8s, ubuntu based

Reference https://microk8s.io/docs



```
microk8s status --wait-ready

microk8s enable dns storage

microk8s enable helm

alias kubectl='microk8s kubectl'

alias helm='microk8s helm'

```
