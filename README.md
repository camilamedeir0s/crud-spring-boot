Banco de dados MySQL em container docker:

$ sudo docker run -d -p 3306:3306 --name meu_mysql     -e MYSQL_ROOT_PASSWORD=root     -e MYSQL_DATABASE=vollmed_api     mysql:latest