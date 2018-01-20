# Docker Swarm Mode

Our Docker cluster compose files.

### Setup

Create a network for `traefik`.

```
docker network create --attachable=true --driver=overlay traefik
```


