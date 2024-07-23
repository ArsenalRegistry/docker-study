```
# 1
docker network create –driver bridge --subnet 192.168.100.0/24 –gateway 192.168.100.254 mynet 
docker network ls
docker network inspect mynet
```
```
# 2
docker run –d –name web –p 80:80 nginx
curl localhost:80

Docker run –d --name appjs –net mynet –ip 192.168.100.100 –p 8080:8080 smlinux/appjs
curl localhost:8080
```
