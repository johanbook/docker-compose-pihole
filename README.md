# docker-compose-pihole

This is a `docker-compose` implementation for [Pi-hole](https://pi-hole.net/),
which is a DNS sinkhole for ads. It uses `Traefik` as a reverse proxy for its
web interface.

## Setup

Create a `.env` file containing the following

```sh
export DOMAIN=<REPLACE-ME>
export EMAIL=<REPLACE-ME>
export TZ=<REPLACE-ME>
export PIHOLE_PASSWORD=<REPLACE-ME>
```

and run

```sh
docker-compose up
```
