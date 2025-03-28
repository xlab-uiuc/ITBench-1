# ITBench: Observability Tools

## Overview
Depending on the scenario domain (SRE or FinOps), the following tools are deployed:
| Tool | Scenario Domain(s) | Repository |
| --- | --- | --- |
| Bitnami Elasticsearch | FinOps, SRE | https://github.com/bitnami/containers |
| Bitnami Kubernetes Event Exporter | FinOps, SRE | https://github.com/bitnami/containers |
| Grafana | FinOps, SRE | https://github.com/grafana/grafana |
| Jaeger | FinOps, SRE | https://github.com/jaegertracing/jaeger |
| Kubernetes Ingress | FinOps, SRE | https://github.com/kubernetes/ingress-nginx |
| Kubernetes Metric Server | FinOps | https://github.com/kubernetes-sigs/metrics-server |
| Loki | FinOps, SRE | https://github.com/grafana/loki |
| OpenCost | FinOps | https://github.com/opencost/opencost |
| OpenSearch | FinOps, SRE | https://github.com/opensearch-project/OpenSearch |
| Prometheus | FinOps, SRE | https://github.com/prometheus/prometheus |

### Installing Observability stack for SRE scenarios
Run:
```bash
make deploy_observability_stack
```

### Uninstalling Observability stack for SRE scenarios
Run:
```bash
make undeploy_observability_stack
```

### Installing FinOps stack (Observability stack + OpenCost + Metrics Server) for FinOps scenarios
Run:
```bash
make deploy_observability_stack
```

### Uninstalling FinOps stack for FinOps scenarios
Run:
```bash
make undeploy_observability_stack
```
