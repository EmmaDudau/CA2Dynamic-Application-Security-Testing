```
$ docker network create network-example

```

```
docker run --name db -e MYSQL_ROOT_PASSWORD=my-secret-password -d mysql:latest

```

```
docker run --network my-network -p 8080:80 phpmyadmin/phpmyadmin

```