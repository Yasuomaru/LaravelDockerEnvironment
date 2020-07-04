# LaravelDockerEnvironment
Docker environment for Laravel


Cmds:
Get up and running: docker-composer up -d --build

npm:
docker-compose run -rm npm [cmd]
docker-compose run -rm npm install
docker-compose run -rm npm run dev

composer:
docker-composer run -rm composer require [package]


artisan:
docker-compose run -rm artisan [cmd]
docker-compose run -rm artisan migrate
