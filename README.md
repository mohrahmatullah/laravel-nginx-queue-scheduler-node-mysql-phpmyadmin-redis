## How to run this project

To run this project you need to have docker and docker-compose installed in your machine.

Take the following steps:

- clone this repository by executing the following command: 'git clone https://github.com/jjuanrivvera99/laravel-nginx-mysql-docker'
- change directory: 'cd laravel-nginx-mysql-docker'
- run command: 'docker-compose pull'
- run command: 'docker-compose up -d'
- 
Enable auth (Laravel 6+):

- run command: docker-compose exec app composer install laravel/ui
- run command: docker-compose exec app php artisan ui vue --auth
- run command: docker-compose exec node npm install
- run command: docker-compose exec node npm run dev
