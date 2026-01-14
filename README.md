# A docker compose for Grafana and Prometheus stack

## Dependencies

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose plugin](https://docs.docker.com/compose/install/linux/)

## Installation

```bash
git clone https://github.com/unleftie/grafana-prometheus-stack-compose.git
cd grafana-prometheus-stack-compose
cp .env.example .env
cp grafana/.env.example grafana/.env
docker compose up -d
```
