# Business Requirements for Monitoring PostgreSQL

## 1. Real-Time Monitoring (prometheus)
- **Requirement**: Provide real-time monitoring of system performance, application health, and infrastructure.
- **Details**:
  - Collect metrics like CPU, memory, disk usage, and network traffic.
  - Monitor application-specific metrics such as response times, error rates, and throughput.
  - Detect anomalies and deviations from expected patterns.

  https://hub.docker.com/r/prom/prometheus/
  https://hub.docker.com/r/prometheuscommunity/postgres-exporter (probably this one as well)

---

## 2. Customizable Dashboards (Grafana)
- **Requirement**: Provide intuitive and customizable dashboards for visualizing metrics.
- **Details**:
  - Allow users to create custom views for specific metrics or systems.
  - Include pre-built dashboards for commonly monitored components (e.g., databases, servers, containers).
  - Enable drill-down capabilities for detailed analysis.

  https://hub.docker.com/r/grafana/grafana
---