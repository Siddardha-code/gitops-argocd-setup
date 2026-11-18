# gitops-platform

GitOps source of truth for the SLO-driven platform on Kubernetes.

- `apps/` Argo CD Application manifests
- `workloads/` Kustomize bases and overlays per service
- `monitoring/` kube-prometheus-stack values, ServiceMonitors, dashboards, alert rules
