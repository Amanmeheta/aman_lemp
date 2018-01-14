#lamp-application

Run Nginx, lamp-application using [Docker]
==========================
## Requirements
Install [Git] and [Docker] and [Docker-Compose]-----------------Rest of the dependecies will get install automatic
==========================
[Docker]:                      https://www.docker.io/
[Compose]:                     http://docs.docker.com/compose/install/

1. In docker-compose.yml we are calling dockerfile and installing the required things
2. In php-7.0-custom folder contain dockerfile
3. htdocs folder contain normal file like *.html,*.php
4. configuration of nginx is present in nginx.conf which has been to integrate as load balancer with other services of lamp application
==========================
1. Start the docker service---
sudo systemctl enable  docker.service
sudo systemctl start  docker.service
==========================
## Usage

1. To run the application----------docker-compose up -d

2. To see the logs of the application------------docker-compose logs

3. To stop the application------------docker-compose stop

