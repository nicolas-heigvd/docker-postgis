# docker-postgis

## Description

Docker-compose default instance to run PostGIS and pgAdmin4 in docker containers


## Setup
1. Copy the given sample env file and adapt it to your environment: `cp .env.sample .env`    
2. Run `docker-compose up --detach` to start the composition.    

## References

- https://towardsdatascience.com/how-to-run-postgresql-and-pgadmin-using-docker-3a6a8ae918b5
- https://levelup.gitconnected.com/creating-and-filling-a-postgres-db-with-docker-compose-e1607f6f882f

## Hint💡

to get containers ip run:

- docker ps -a
- docker inspect --format='{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' <container_id>
