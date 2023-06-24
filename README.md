For installation
############### General ######################
1. Copy .env.example to .env
2. Change the values in .env



############### Laravel Configuration ######################
-> Initial install

1. Copy ./app_envs/laravel.example.env to ./laravel_project/.env
2. Change the credentials (DB) in ./laravel_project/.env
3. RUN `docker compose build`
4. RUN `docker compose up -d`
5. Get inside the container: `docker exec -it {container_name} /bin/bash`
6. RUN `composer install`
7. RUN `php artisan migrate`
