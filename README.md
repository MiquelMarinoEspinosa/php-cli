PHP cli basic project to setup a very simple DDD architecture with docker

- Create file .env with your ip address based on .env.dist
- docker-compose up
- docker exec -i -t miquel.php-cli composer install
- docker exec -i -t miquel.php-cli vendor/bin/phpunit
