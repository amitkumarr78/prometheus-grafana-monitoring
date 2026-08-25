# Prometheus + Grafana Windows Monitoring

A local monitoring project built using **Prometheus, Grafana, and Windows Exporter** to monitor Windows system resources.

The complete setup runs locally on a Windows machine without using AWS, Kubernetes, Docker, or any cloud infrastructure.

---

## Project Overview

This project demonstrates how Prometheus can collect system metrics from a Windows machine using Windows Exporter and how Grafana can visualize those metrics through dashboards.

### Monitoring Flow

```text
Windows Machine
      |
      v
Windows Exporter
      |
      | Metrics
      v
Prometheus
      |
      | PromQL
      v
Grafana
      |
      v
Monitoring Dashboard