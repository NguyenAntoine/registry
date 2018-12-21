# Registry docker-compose

[Using Registry Docker Image](https://docs.docker.com/registry/deploying/)

## Installation

Create the `.env` file from [.env.dist](.env.dist) example with the
environment variables from [docker let's encrypt nginx proxy](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion/wiki/Basic-usage)

```bash
docker-compose up -d
```

## Update docker images

```bash
./updateDockerImages.sh
```
