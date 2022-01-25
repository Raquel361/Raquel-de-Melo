docker container run -d --AulaInfraCloudMysql mysql -v 
/var/lib/mysql -e MYSQL_ROOT_PASSWORD='123' -e bind-address=0.0.0.0 mysql:5.7
docker network inspect bridge
docker container run --AulaInfraCloudNginx docker-nginx -p 80:80 -d nginx -e DBHOST=192.168.0.61
