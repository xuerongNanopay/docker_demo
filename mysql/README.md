# Mysql Docker Cheat Sheet

```
docker pull mysql:8.0
```

```
docker run --name mysql -p 3307:3306 -v ${PWD}/volumn/mysql/:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=123456  -d mysql:5.7

```

```
docker exec -it mysql mysql -u root -p
```
