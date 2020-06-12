# DEPRECATED

This chart is deprecated now that the official one is available, at https://github.com/kubernetes/dashboard/tree/master/aio/deploy/helm-chart/kubernetes-dashboard

To install the official chart:

```
# Add kubernetes-dashboard repository
helm repo add kubernetes-dashboard https://kubernetes.github.io/dashboard/
# Deploy a Helm Release named "my-release" using the kubernetes-dashboard chart
helm install kubernetes-dashboard/kubernetes-dashboard --name my-release
```