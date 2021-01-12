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

## Dependencies

To install, run `go get -u <dependency>` for the following:

```
github.com/gorilla/mux
github.com/sirupsen/logrus
github.com/jinzhu/gorm
github.com/go-sql-driver/mysql
github.com/jinzhu/gorm/dialects/mysql
github.com/rs/cors
```
