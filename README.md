# Guacamole kubernetes installation

This repostiory describes how to install and manage guacamole on kubernetes environment.

## How to deploy
```bash
$ kubectl apply -k base
```

## Components
- PostgreSQL database: https://hub.docker.com/_/postgres
- Guacamole frontend: https://hub.docker.com/_/postgres
- Guadc backend: https://hub.docker.com/_/postgres

## Version history

**Versio 0.1**: Initial architecture of guacamole on kubernetes

## Authors
- Jesse Korhonen
