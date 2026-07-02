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

# Pictures
## Prometheus targets
The following image shows the prometheus target and the minecraft server target (ATM10) and the state
<img width="1905" height="446" alt="image" src="https://github.com/user-attachments/assets/5459a52a-892b-4305-9070-787c50b9e4fe" />

## Grafana dashboard

The following image shows the grafana dashboard used to visualize most of the metrics gathered from the monitored vm
<img width="2246" height="1119" alt="image" src="https://github.com/user-attachments/assets/3321b419-1b73-4866-bec3-a64536a353f8" />
I haven't made this dashboard. It can be found here : https://grafana.com/grafana/dashboards/1860-node-exporter-full/
