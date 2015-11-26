# Michale's Home Development Environment


- Dockerfile

- mysql

	`sudo docker run --name some-mysql -v /web/data1:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=111 -d mysql`
- web server

	`sudo docker run --name some-app2 --link some-mysql:mysql -v /web/drupal8:/app/ -it  hanfeng/php_base1`

# Useful Command

- docker ps -l
- docker inspect some-mysql
- docker attach some-mysql

Ctrl + P, Ctrl + Q

# todo 
- Dockerfile install open-ssh, drush, apache2-rewrite


- php.config & apache2.config & nginx.conf  & php-cgi.config
