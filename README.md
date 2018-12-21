# Registry docker-compose

[Using Registry UI Docker Image](https://hub.docker.com/r/joxit/docker-registry-ui/)

## Installation

Create the `.env` file from [.env.dist](.env.dist) example with the
environment variables from [docker let's encrypt nginx proxy](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion/wiki/Basic-usage)
Create the `.env.ui` file from [.env.ui.dist](.env.ui.dist) example with the
environment variables from [docker let's encrypt nginx proxy](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion/wiki/Basic-usage)

```bash
docker-compose up -d
```

## Update docker images

```bash
./updateDockerImages.sh
```
