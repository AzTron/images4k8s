# mysql-alpine
mysql base on alpine

# build image
docker build -t harmonycloud/mysql-alpine .
docker run -ti -p 3306:3306 harmonycloud/mysql-alpine

# Usage
docker run -ti --name mysql-alpine -p 3306:3306 -e MYSQL_DATABASE=harmonycloud -e MYSQL_USER=harmonycloud -e MYSQL_PASSWORD=harmonycloud -e MYSQL_ROOT_PASSWORD=123456789 harmonycloud/mysql-alpine
