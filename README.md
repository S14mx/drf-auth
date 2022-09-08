# LAB - Class 33

## Project: Authentication & Production Server

## Author: Sergii Otryshko

How to initialize/run your application:

run `docker-compose up --build` command

to test routes:
GET http://localhost:8000/api/v1/cars/ - car list, requires token
POST http://localhost:8000/api/token/ - to obtain token, requires username and password in body of the request
POST http://localhost:8000/api/token/refresh/ - to refresh token, requires token