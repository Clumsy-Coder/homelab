# portainer

Using portainer to manage docker images and container via web gui

## Getting started

### Steps

1. Run command to start portainer
```bash
docker compose up -d --remove-orphans --force-recreate
```
2. check if all containers are deployed
```bash
docker ps
```
3. Go to `https://<ip address>:9443` to open portainer
