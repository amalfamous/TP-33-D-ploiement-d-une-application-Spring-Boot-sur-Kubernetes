## execute cette commande pour la bd:
docker run --name tp33-mysql  -e MYSQL_ROOT_PASSWORD=   -e MYSQL_ALLOW_EMPTY_PASSWORD=yes  -e MYSQL_DATABASE=tp33-k8s  -p 3306:3306  -d mysql:8.0
