inside postgres directory should be created additional "postgres_data" directory. 

structure should be like this:
```
docker_postgres
 - postgres
 - - postgres_data
```

inside "postgres_data" directory will be stored your sql DB data. Shared with container via volume in docker-compose file.

folder can be created with:
```
mkdir -p postgres/postgres_data
```