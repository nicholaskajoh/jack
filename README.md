# Jack
A project that demonstrates how to run multiple apps on one server using Docker and Traefik.

## Dev setup
- Clone/download this repo
- Install Docker and Docker Compose
- Run `docker-compose up` in project root

## Prod setup
- Provision a server
- Configure a domain (and sub-domains) for your server
- Install Git
- Fork and clone this repo
- Install Docker and Docker Compose
- Edit *docker-compose.prod.yml* and *traefik.toml* as appropriate
- Run `docker-compose -f docker-compose.prod.yml up --build -d` in project root