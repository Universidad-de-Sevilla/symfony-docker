# Symfony 5 Docker Stack

* alpine
* MariaDB
* NGINX
* PHP-FPM
* Composer

A Proof-of-concept of a running Symfony 5 application inside containers

```
git clone https://github.com/Universidad-de-Sevilla/symfony-docker

cd symfony-5-docker

cd docker

docker-compose up
```


### PHP (PHP-FPM)

Composer is included

```
docker-compose run php-fpm composer 
```

To run fixtures

```
docker-compose run php-fpm bin/console doctrine:fixtures:load
```


### Basado en 

* https://www.martinpham.com/2019/12/10/symfony-5-development-with-docker/
* https://gitlab.com/martinpham/symfony-5-docker

