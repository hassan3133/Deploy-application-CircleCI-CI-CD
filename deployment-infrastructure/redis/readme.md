``` bash

helm repo add bitnami https://charts.bitnami.com/bitnami

helm repo update

#installation
kubectl create namespace dtuc
helm install redis --namespace=dtuc oci://registry-1.docker.io/bitnamicharts/redis -f dtuc-dev.values.yaml
```
