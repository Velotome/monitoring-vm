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
The following image shows the two target I'm monitoring. The first is the machine with the minecraft server and the server. The second is the "monitoring" machine prometheus is running on
<img width="1910" height="487" alt="image" src="https://github.com/user-attachments/assets/350660bf-6623-475e-803f-6c96788a12fb" />


## Grafana dashboard
The following image shows the grafana dashboard I built to visualize most of the metrics gathered from the monitored machine and the minecraft server
<img width="1909" height="720" alt="image" src="https://github.com/user-attachments/assets/392366b1-4f3e-4683-9f92-66548243cc01" />
