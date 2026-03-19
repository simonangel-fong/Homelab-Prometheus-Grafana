# Homelab-Prometheus-Grafana
A repo for prometheus+grafana homelab.


```sh
kubectl create secret generic grafana-cloud-secret \
  --from-literal=username=user_id \
  --from-literal=password=token \
  -n monitor
```