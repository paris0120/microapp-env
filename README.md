## Micro App Environment
All servers needed for micro apps are provided here through docker containers.

### Warnings
All servers are for test and dev only. Further configurations are needed for prod.

#### How to use
You can either start individual server with

```
docker compose -f <server-name>.yml up
```

or start all necessary servers with 

```
docker compose -f app.yml up
```
