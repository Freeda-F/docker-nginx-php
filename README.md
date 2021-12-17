# Docker Nginx PHP Application
This is a simple example for running a docker container with PHP-FPM and NGINX using docker-compose.

## Requirements
- [Install docker](https://docs.docker.com/engine/install/)
- [Install docker-compose](https://docs.docker.com/compose/install/)

## Usage

1. A PHP application set up inside a folder - web_app.
2. The SSL certificate files inside the folder - certs.
3. Custom nginx.conf file - nginx.conf


## Provisioning

1. Clone this repository
```
https://github.com/Freeda-F/docker-nginx-php.git
```
2. Switch to the cloned directory
```
cd docker-nginx-php
```
3. Start the docker containers using
```
docker-compose up -d
```

## Result

![image](https://user-images.githubusercontent.com/93197553/146550943-bee05f75-e256-4ddf-9c60-03c14608fe21.png)
