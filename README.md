# Helm charts!

This repo is for testing out helm charts.

Thanks to https://medium.com/@mattiaperi/create-a-public-helm-chart-repository-with-github-pages-49b180dbb417

updates:
```
helm package ../teleport/examples/chart/teleport-cluster/ ../teleport/examples/chart/teleport-kube-agent/
helm repo index --url https://timothy-spencer.github.io/helm-charts/ .
```

