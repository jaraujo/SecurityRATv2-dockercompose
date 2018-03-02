# JHipster generated Docker-Compose configuration

## Usage

Launch all your infrastructure by running: `docker-compose up -d`.

## Configured docker services

### Service registry and configuration server:
- [Consul](http://localhost:8500)

### Applications and dependencies:
- caseManagement (microservice application)
- caseManagement's no database
- gateway (gateway application)
- gateway's mariadb database
- requirementManagement (microservice application)
- requirementManagement's mariadb database

### Additional Services:

- [Prometheus server](http://localhost:9090)
- [Prometheus Alertmanager](http://localhost:9093)
- [Grafana](http://localhost:3000)
- [Keycloak server](http://localhost:9080)
