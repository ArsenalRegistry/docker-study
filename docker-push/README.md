```
docker login ghcr.io -u ArsenalRegistry -p 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11

# 뒤에 11값은 지워야합니다.

docker images -a

docker tag <image_id> ghcr.io/arsenalregistry/webserver-사번:latest

docker push ghcr.io/arsnealRegistry/webserver-사번:latest

```
