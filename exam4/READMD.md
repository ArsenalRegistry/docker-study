```
# docker run
ls /dbdata
docker run -d --name db -v /dbdata:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=pass mysql:latest
```
```
# db pod terminal
docker exec -it db /bin/bash
mysql -u root -ppass
```
```
# In pod Termninal
show databases;
CREATE DATABASE ktds;
show databases;
exit
```
```
# Out pod Terminal(host)
ls /dbdata
docker rm -f db
ls /dbdata
```
