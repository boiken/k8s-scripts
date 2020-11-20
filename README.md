# k8s-scripts
Kubernetes script adapted from me

**Usage**
> ./pod-status-monitor.sh $(kubectl get pod -o jsonpath="{.items[0].metadata.name}")
