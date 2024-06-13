```
docker login ghcr.io -u ArsenalRegistry

# 뒤에 11값은 지워야합니다.

password: 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11

docker images -a

docker tag <image_id> ghcr.io/arsenalRegistry/webserver-사번:latest

docker push ghcr.io/arsnealRegistry/webserver-사번:latest

```
