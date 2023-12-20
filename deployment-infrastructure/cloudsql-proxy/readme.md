https://github.com/rimusz/charts/tree/master/stable/gcloud-sqlproxy

``` bash

helm repo add rimusz https://charts.rimusz.net

helm repo update
kubectl create namespace cloudsql-proxy
#installation
helm install gcloud-sqlproxy --namespace=cloudsql-proxy rimusz/gcloud-sqlproxy -f values.yaml
```


