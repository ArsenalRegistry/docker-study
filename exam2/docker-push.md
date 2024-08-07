```
docker login ghcr.io -u ArsenalRegistry -p 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1 # 뒤에 숫자 1 제외
```
```
docker images -a
```
```
docker tag <image_id> ghcr.io/arsenalregistry/webserver-사번:latest
```
```
docker push ghcr.io/arsenalregistry/webserver-사번:latest
```
