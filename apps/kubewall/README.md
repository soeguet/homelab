```sh
helm install kubewall oci://ghcr.io/kubewall/charts/kubewall -n kubewall-system --create-namespace
```

```sh
helm template kubewall oci://ghcr.io/kubewall/charts/kubewall \
  -n kubewall-system \
  --create-namespace \
  --output-dir .
```
