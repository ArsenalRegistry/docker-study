```
docker login testcoeregistry.azurecr.io -u testCoeRegistry -p z+XVGtxTPSAGhDxsTjPwW+3etblWGcXXiwUkshSyO++ACRAIP56Z1 # 뒤에 숫자 1 제외
```
```
docker images -a
```
```
docker tag <image_id> testcoeregistry.azurecr.io/testCoeRegistry/8사번/webserver:latest
```
```
docker push testcoeregistry.azurecr.io/testCoeRegistry/8사번/webserver:latest
```
