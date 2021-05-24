## Setup

```sh
REDIS_PASSWORD=$(openssl rand -base64 16) docker-compose up -d && echo "redis password: ${REDIS_PASSWORD}"
```
