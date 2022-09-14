# Redis with Commander Based on Docker

Quickly deploy a Redis with a Web-based Redis Commander by using docker.

## Usage 

clone the code

```bash
git clone https://github.com/banbanpeppa/docker-redis-with-commander.git
```

start the redis and commander

```bash
cd docker-redis-with-commander
docker-compose up -d
```

## Config

Change the config by modifying `.env`

```
REDIS_PORT=6379
REDIS_HOST_PASSWORD=redis

COMMANDER_HTTP_USER=commander
COMMANDER_HTTP_PASSWORD=commander
COMMANDER_PORT=8081
```
