## Networking

``` shell
$ docker network create hello
$ docker network inspect hello
```

## Server

``` shell
$ cd server
$ docker build -t helloserver .
$ docker run -p 9000:9000 --network hello helloserver
```
