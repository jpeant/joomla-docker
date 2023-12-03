# Joomla + MariaDB + phpMyAdmin on Docker. 
### Written by JpeAnt

Use for testing ONLY in current state. 
For production change usernmames, passwords and ports. Recomending using a Nginx Reverse Proxy for https trafic.

## What is this?
A fast way to spin up Joomla CMS using Docker. Compose file imports latest images for Joomla, MariaDB and phpMyAdmin, makes persistant volumes.

## How do I access Joomla?
Open `http://DOCKER_HOST:8034`

## How do I access phpMyAdmin?
Open `http://DOCKER_HOST:8033`

## Where is my stuff?
Joomla and MariaDB are mounted as docker persistant volumes.


