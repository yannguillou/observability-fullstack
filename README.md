Full Stack observability for metrics and logs monitoring
- Grafana to visualize
- Minio Object storage (single instance)
- Grafana Mimir relying on  Minio for persistent metrics storage
- Loki relying on Minio for Logs
- Prometheus relying on Mimir for Metrics
- PromGen Web UI to manage Prometheus configuration
- Syslog-NG+PromTail to feed Loki
  
