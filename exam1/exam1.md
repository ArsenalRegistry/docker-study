```
# 1
docker search nginx # nginx 이미지 찾기 
```

```
# 2
ls /var/lib/docker/overlay2
docker pull nginx # pull image
ls /var/lib/docker/overlay2 # check layer
```

```
# 3
docker run --name web -d -p 80:80 nginx
docker ps -a 
curl localhost:80
```

```
# 4
docker rm -f web
docker rmi nginx
ls /var/lib/docker/overlay2 # check layer 
```
