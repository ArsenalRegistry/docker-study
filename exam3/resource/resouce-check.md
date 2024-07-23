```
docker build -t stress .
```
```
docker run -m 100m --memory-swap 100m stress:latest stress --vm 1 --vm-bytes 90m -t 5s
```
```
docker run -m 100m --memory-swap 100m stress:latest stress --vm 1 --vm-bytes 150m -t 5s
```
```
docker run -m 100m stress:latest stress --vm 1 --vm-bytes 150m -t 5s
```
