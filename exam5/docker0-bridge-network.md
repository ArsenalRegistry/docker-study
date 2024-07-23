```
ip addr
brctl show

docker run --name c1 –it busybox
ip addr
ping –c 3 8.8.8.8
docker inspect c1

docker run --name c2 –it busybox
ip addr
ping –c 3 8.8.8.8
docker inspect c2

docker run –d –p 80:80 –name web1 nginx

curl 172.17.0.4

iptables –t nat -L -v
```
