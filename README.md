# code6
```
docker-compose up -d && sleep 15 && docker run -d -p 8080:80 --name code6 -e MYSQL_HOST=MySQL_Host -e MYSQL_PORT=3306 -e MYSQL_DATABASE=code6 -e MYSQL_USERNAME=root -e MYSQL_PASSWORD=123456 code6:latest && sleep 10 && docker exec -it code6 /bin/bash -c 'php artisan code6:user-add your_mail@mail.com password'
```
