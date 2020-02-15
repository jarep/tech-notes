
# Docker:

- Basic commands

	`docker version`

	`docker run`

- Run postgres

	`docker run --name my-postgres -p 5432:5432 -e POSTGRES_PASSWORD=password -d postgres`

## Volumes

- List of volumes

  `docker volumes -l`



# Docker compose

-  removes the containers and default network, but preserves volumes

  `docker-compose down`

- removes the containers, default network and volumes

  `docker-compose down --volumes`

- remove orphans

  `docker-compose down --remove-orphans`
