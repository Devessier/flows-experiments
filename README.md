## Setup

To start Redis locally:

```sh
docker run --name some-redis -d redis redis-server --save 60 1 --loglevel warning
```
