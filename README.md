# Publicando Imagem Laravel - Part 1

This repository contains the code that solves the challenge "Publicando Imagem Laravel - Parte 1" from DevOps course of Code Education.

In this first part of the challenge, it is suppose to configure a Laravel environment using `docker-compose` with:
 - Nginx
 - PHP-FPM
 - Redis
 - MySQL

 **Note**: when accessing the Laravel application,you will see the error:
```browser
Warning: require(/var/www/public/../vendor/autoload.php): failed to open stream: No such file or directory in /var/www/public/index.php on line 34

Fatal error: require(): Failed opening required '/var/www/public/../vendor/autoload.php' (include_path='.:/usr/local/lib/php') in /var/www/public/index.php on line 34
```

This error is expected by the challenge.

## Goal

The goal of the challenge is to learn `docker` and `docker-compose` in practice.

## Usage

To run this code, in a terminal, execute:

```bash
docker-compose up -d
```

Then, in a browser enter:

```bash
localhost:8000
```

To stop the containers and remove them, execute:
```bash
docker-compose down
```