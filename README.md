# Demo app (services)

## Description

The project consists of two simple services:
 - spring-boot-app - Java application with SpringBoot
 - node-app - Node.js application with Express

 ##  Instructions for running microservices project with docker-compose

 ## Steps
 1. Postgres running on port 5432. You need to be sure that this port is not used by another service
 2. Install docker egine from https://docs.docker.com/engine/install/
 3. Install docker compose from https://docs.docker.com/compose/install/
 4. Clone this repository 'git clone https://github.com/augljesa1/abhtask.git'
 5. Navigate to cloned repository
 6. Run 'docker-compose build' for building images
 7. Run 'docker-compose up' for running dockerized microservices app
 8. Once all services (containers) are running, execute './health-check.sh'

