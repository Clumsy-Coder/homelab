# pihole-unbound

Using pihole and unbound using docker compose in a Raspberry Pi

<!--
embeding image and link to video

obtained from
- https://stackoverflow.com/a/29862696/3053548
- https://stackoverflow.com/a/62980984/3053548
-->

[![Jim's Garage running pihole and unbound using docker](http://img.youtube.com/vi/Y3nm519xHfw/0.jpg)](https://www.youtube.com/watch?v=Y3nm519xHfw "Running pihole and unbound using docker")

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
5. Go to `http://<ip address>/admin` to go to admin portal

## Credits

Obtained from

- https://github.com/JamesTurland/JimsGarage/blob/c4f2039/Unbound/docker-compose.yaml
