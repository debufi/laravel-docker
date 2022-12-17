# laravel-docker
Docker compose to setup nginx, php and mysql for laravel 8

## Images
1. nginx → nginx:1.20
2. php → php:8.1-fpm
3. mysql → mysql:8

## Deployment using Docker
1. Deploy nginx, php-fpm, and mysql using docker-compose
    ```bash
    docker-compose up -d
    ```
2. Stop container
    ```bash
    docker-compose stop
    ```
