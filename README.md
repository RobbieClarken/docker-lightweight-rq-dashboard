# Alpine RQ Dashboard Docker Image

Lightweight Docker image to run RQ Dashboard.

## Usage

```
docker run --detach --publish 9181:9181 --restart=unless-stopped \
           robbieclarken/lightweight-rq-dashboard -H REDIS_HOST
```
