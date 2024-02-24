# grafana, loki and promtail on docker
like Prometheus, but for logs.

## Description
This repository contains a Docker Compose configuration for deploying Grafana, Loki, and Promtail, providing a comprehensive solution for log aggregation and visualization.


## Instructions
1. Clone this repository.
```bash
git clone https://github.com/rastinsenobari/grafana-loki-promtail && cd grafana-loki-promtail
```

2. Link your log directory to logs directory.

3. Start services.
```bash
docker compose up -d
```
4. Access Grafana via your web browser at http://localhost:3000 (default credentials: admin/admin).

5. Create a dashboard with loki data sources

## Contributing
If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue. Don't forget to give the project a star! Thanks again!