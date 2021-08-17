# Single page App with FastApi and Vue.js

Currently work in progress

How to run:
```
docker-compose up -d
```

Some commands:
```
$ docker-compose exec backend aerich init -t src.database.config.TORTOISE_ORM
$ docker-compose exec backend aerich init-db
$ docker-compose exec backend aerich migrate
$ docker-compose exec backend aerich upgrade
```