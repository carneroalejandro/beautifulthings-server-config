# beautifulthings-server-config
Config and service files for the google cloud server

## Enable RBAC Creation

```bash
kubectl create clusterrolebinding cluster-admin-binding --clusterrole cluster-admin --user caleb@doxsey.net
```

## Create Secrets

```bash
kubectl create secret generic cloudflare --from-literal=email='EMAIL' --from-literal=api-key='API_KEY'
```
