# OpenTelemetry Collector Setup with Tempo, Mimir, and Loki

This setup uses Docker Compose to run the OpenTelemetry Collector along with Grafana Tempo, Mimir, and Loki for tracing, metrics, and logging respectively.

## Prerequisites
You can use Docker/Docker Compose or Podman/Podman Compose to run the setup.


## Services
- OpenTelemetry Collector
- Tempo
- Mimir
- Loki
- Grafana

Start the services using Docker Compose.
```bash
docker-compose up -d
```

Start the services using Podman Compose.
```bash
podman-compose up -d
``` 
Access Grafana at `http://localhost:3000`.


To stop all services, run:

```sh
docker-compose down
```

