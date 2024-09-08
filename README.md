# Guacamole kubernetes installation

This repostiory describes how to install and manage guacamole on kubernetes environment.

This isn't production ready in any means!

## How to deploy
```bash
# Apply the kubectl program
# Remember to point the ingress hostname to ingress ip.
$ kubectl apply -k base
```

## Components
- PostgreSQL database: https://hub.docker.com/_/postgres
- Guacamole frontend: https://hub.docker.com/r/guacamole/guacamole
- Guadc backend: https://hub.docker.com/r/guacamole/guacd

## Version history

**Versio 0.1**: Initial architecture of guacamole on kubernetes

## Authors
- Jesse Korhonen
