# To Up the container

```
docker-compose --env-file ./.env up -d
```


# To get the hostname of postgresql

```
docker inspect <CONTAINER_ID_OF_POSTGRESQL> | grep IPAddress
```

