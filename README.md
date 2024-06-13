# Projeto Laravel Jetstream (Vue/InertiaJS) Dockerizado

## Depois de clonar:

+ cd jetstream-docker
+ Criar .env

+ Alterar .env
    + DB_CONNECTION=mysql
    + DB_HOST=db
    + DB_PORT=3306
    + DB_DATABASE=laravel
    + DB_USERNAME=root
    + DB_PASSWORD=root
    + REDIS_CLIENT=phpredis
    + REDIS_HOST=127.0.0.1
    + REDIS_PASSWORD=null
    + REDIS_PORT=6379
    + MAIL_MAILER=smtp
    + MAIL_HOST=mailhog
    + MAIL_PORT=1025

+ Rodar comandos make

`make setup`

`make terminal`

+ No terminal do docker rodar

`npm install`

`npm run build`

`php artisan migrate`

+ Gerar laravel app key

`php artisan key:generate`

## Pronto, o app vai estar rodando no localhost:8080
