# MY SQL DOCKER
## My ip docker
docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' my_mysql_db

or

docker inspect my_mysql_db | grep "IPAddress"

172.20.0.2

mydata
user
password
