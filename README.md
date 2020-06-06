# Synology_dashboard_grafana (Dockerized)
A grafana dashboard for monitoring Synology NAS

Dependencies
InfluxDB as the time-series database
Telegraf as the collector

Quick Start
- git clone this repo
- cd Synology_dashboard_grafana
- nano etc/telegraf/telegraf.conf
- Add your influxdb address, targets, and community string
- Run 
    ```docker-compose up -d```
- Look at the logs for errors
    ```docker logs -f telegraf```

