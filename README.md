# Joomla + MariaDB + phpMyAdmin on Docker. 
### Written by JpeAnt

## Environment details:
- MySQL root password: 12345678
- Joomla database name: joomla
- MySQL hostname: mysql

# FAQ


## What is this?
A fast way to spin up joomla using Docker.

## How do I access Joomla?
Open `http://DOCKER_HOST:80`

## How do I access phpMyAdmin?
Open `http://DOCKER_HOST:81`

## Where is my stuff?
Joomla and MySQL are mounted as docker volumes inside the `code` and `database `directories.

(Changes are persisted accross container restart \ removal)

