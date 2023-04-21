# MING (MQTT, InfluxDB, N3uron, Grafana)

The MING stack is a popular combination of open-source technologies used for building scalable and real-time Industrial Industrial IoT data processing and visualization systems.

* MQTT is a lightweight messaging protocol designed for constrained devices and low-bandwidth, high-latency or unreliable networks, commonly used for IoT applications.
* InfluxDB is a scalable, high-performance, distributed, and fault-tolerant time-series database that is optimized for storing and querying large volumes of timestamped data.
* N3uron is an Industrial Edge Platform for DataOps that streamlines the flow of data between industrial devices and business applications, either on-premise or in the cloud.
* Grafana is an open-source platform for data visualization and monitoring that allows users to create, explore, and share dashboards and alerts for a wide range of data sources, including databases, APIs, and metrics.

## Deploy

```shell
docker compose -f docker-compose.yml up -d
```

Launch with Telegraf

```shell
docker compose -f docker-compose.yml -f docker-compose.telegraf.yml up -d
```

## About Us

At [N3uron](https://n3uron.com/) our mission is to design modern Industrial IoT software solutions to empower organizations to accomplish any data management project, whilst minimizing technological and financial obstacles.
