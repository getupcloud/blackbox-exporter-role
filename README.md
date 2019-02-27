Atom Packages
=========

Adding blackbox-exporter to an existing prometheus-operator installation


Role Variables
--------------

```yaml
blackbox_helm_release_name: Helm Release name to install blackbox-exporter chart
blackbox_k8s_namespace: Kubernetes namespace to install blackbox-exporter chart
endpoints: List of endpoints to monitor with blackbox-exporter
prometheus_k8s_name: Kubernetes Prometheus CRD name
prometheus_k8s_namespace: Kubernetes namespace from the existing Prometheus CRD
prometheus_k8s_secret: Kubernetes secret storing job_config additionalScrapeConfig
```
