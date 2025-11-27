# Nginx Proxy manager

Using Nginx Proxy manager

<!--
embeding image and link to video

obtained from
- https://stackoverflow.com/a/29862696/3053548
- https://stackoverflow.com/a/62980984/3053548
-->

[![Lawrence systems: Self-Hosted SSL Simplified: Nginx Proxy Manager](http://img.youtube.com/vi/jx6T6lqX-QM/0.jpg)](https://www.youtube.com/watch?v=jx6T6lqX-QM "Self-Hosted SSL Simplified: Nginx Proxy Manager")

## Getting started

You will need to use `.env` when running the docker containers.

### Steps

1. Copy `.env.example` to `.env`
```bash
cp .env.example .env
```
2. update the variables accordingly
3. start docker containers
```bash
docker compose up -d --remove-orphans --force-recreate
```
4. check all containers are deployed
```bash
docker ps
```
5. Go to `http://<ip address>:81` to go to admin portal

## Credits

Obtained from

- https://forums.lawrencesystems.com/t/nginx-proxy-manager-docker/24147
- https://nginxproxymanager.com/setup/
