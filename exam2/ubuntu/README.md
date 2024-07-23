```
# 5
docker build -t webserver:v1 .
```
```
# 6
docker run -d -p 80:80 --name web webserver:v1
docker ps -a
curl localhost:80
```
```
#7
docker run -d -p 8080:8080 --name web1 hellojs
docker ps -a
curl localhost:8080
```
