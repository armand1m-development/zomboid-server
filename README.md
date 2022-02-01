## zomboid-server-k8s

kubernetes + istio files to upload a zomboid server to the cluster.

### secrets

```sh
kubectl create secret generic zomboid-server-secrets \
--from-literal=server_password='<server-pass>' \
--from-literal=admin_password='<admin-pass>'
```
