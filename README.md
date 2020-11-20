# k8s-scripts
Kubernetes script adapted from me

* [podstatusmonitor](pod-status-monitor.sh) - script monitors the pod status and a deployment Readiness.Check status is 'Running' and that all containers are ready. Returns 0 if ready. Returns 1 if not ready.

**Usage**

``` ./pod-status-monitor.sh $(kubectl get pod -o jsonpath="{.items[0].metadata.name}") ```
