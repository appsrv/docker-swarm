# Docker Swarm Mode

Our Docker cluster compose files.

### Setup

Networks

```
docker network create --attachable=true --driver=overlay traefik
docker network create --attachable=true --driver=overlay data
docker network create --attachable=true --driver=overlay redis
```


