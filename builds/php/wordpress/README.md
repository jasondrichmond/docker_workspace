docker run -h wordpress.local -d --privileged -p 80:80 -p 2222:22 --name wordpress-6.4.2 --network myNetwork -v d:/docker/volumes/php/wordpress-6.4.2/wordpress:/var/www/html wordpress-6.4.2