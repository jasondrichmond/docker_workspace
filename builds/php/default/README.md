docker run -h web.local -d --privileged -p 80:80 -p 2222:22 --name php --network myNetwork -v d:/docker/volumes/php/default:/var/www/html php:8.2.14-fpm