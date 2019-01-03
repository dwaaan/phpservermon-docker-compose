# phpservermon-docker-compose

Docker Compose file for PHP Server Monitor (from https://www.phpservermonitor.org/)


## 1. Clone Repo
- git clone https://github.com/dwaaan/phpservermon-docker-compose

## 2. Edit docker-compose.yml
- make sure to set your own passwords if setting up in production environment
- set a custom port if required, default is 8082

## 3. Running
- docker-compose up to run interactive
- docker-compose up -d to run in background


Then go to http://DOCKER_HOST:[port]
