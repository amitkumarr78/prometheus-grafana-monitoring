<img width="1920" height="1080" alt="Screenshot 2026-08-26 005035" src="https://github.com/user-attachments/assets/9a088658-8aac-4ee9-95b0-ab9b42383535" />

# Prometheus + Grafana Windows Monitoring

A local monitoring project built using **Prometheus, Grafana, and Windows Exporter** to monitor Windows system resources.

The complete setup runs locally on a Windows machine without using AWS, Kubernetes, Docker, or any cloud infrastructure.

---

## Project Overview

This project demonstrates how Prometheus can collect system metrics from a Windows machine using Windows Exporter and how Grafana can visualize those metrics through dashboards.

<img width="1920" height="1080" alt="Screenshot 2026-08-26 005912" src="https://github.com/user-attachments/assets/4f5a2ed1-661e-4e69-b9b7-87e6fa97b4a4" />

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
