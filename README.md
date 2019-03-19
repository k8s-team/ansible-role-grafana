# ansible-role-grafana

# Get admin username and password

```bash
kubectl get secrets grafana -o=jsonpath='{.data.admin-user}' | base64 --decode
```

```bash
kubectl get secrets grafana -o=jsonpath='{.data.admin-password}' | base64 --decode
```
