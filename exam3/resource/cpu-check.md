```
# apt-get install htop

docker run --cpuset-cpus 1 --name c1 -d stress:latest stress --cpu 1

docker stop c1
docker rm c1

docker run --cpuset-cpus 0-1 --name c1 -d stress:latest stress --cpu 1
htop
docker stop c1
docker rm c1
```

```
docker run -c 2048 --name cload1 -d stress:latest
docker run -c 1024 --name cload2 -d stress:latest
docker run -c 512 --name cload3 -d stress:latest
docker run -c 512 --name cload4 -d stress:latest
```
```
# monitoring
docker stats cload1
docker stats
```
