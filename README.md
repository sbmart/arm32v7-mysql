# arm32v7-mysql
5.7 mysql for docker container on ARM32

docker build --tag mysql-server:1.0 .

docker run --publish 3306:3306 --detach --name mysql-57 mysql-server:1.0