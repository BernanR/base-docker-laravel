## Base Code to start a project using docker.
 - what do we heve here
    - Laravel 10
    - PostgreSql
    - pgAdmin4
    - Redis

## How to install and run this project

1. ```git clone https://github.com/BernanR/brn-OM30-desafio.git```
2. ```cd application```
3. ```composer install```
3. Copy ```.env.example``` to ```.env```
4. ```docker-compose build```
5. ```docker compose up -d```
6. disponível na url ```127.0.0.1:8080```

## Create a serve on pgAdmin4

1. Open the pgAdmin4 panel ```http://localhost:5050/```
  - User and password:
    - User: admin@admin.com
    - Senha: password

2. ```For this application you must use this setup, but also you can change it:```
  - Host: db
  - Port: 5432
  - Username: root
  - Password: password