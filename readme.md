- A laravel application with docker.

Services:
 -  Nginx
 -  Php-fpm
 -  Mysql
 -  Redis

Start:
`docker-compose up -d`

Install dependencies:
`docker-compose exec app composer install`