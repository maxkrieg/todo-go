## Todo API in Go

A simple Todo API written in Go with a MySQL database

## Commands:

Start MySQL Server DB:

```
docker-compose up -d
```

Start application:

```
go run todolist.go
```

Shell into mysql docker container:

```
docker exec -it todo-go_db_1 mysql -uroot -proot
```
