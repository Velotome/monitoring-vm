# monitoring-vm
Monitoring vm using prometheus + grafana

This setup currently monitor the metrics of a vm running a Minecraft server. Metrics are gathered by a Node_exporter on the node

crontab is used to start node_exporter and the mc server on startup

# Technologies used

- Prometheus & node_exporter
- Grafana
- Docker & docker compose
- crontab
- ProxmoxVE
