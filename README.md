# docker-starter-commands
A private repository to contain all docker start commands

### database
- docker run  -p 5432:5432 --name postgres -e POSTGRES_PASSWORD=password -e PGDATA=/var/lib/postgresql/data/pgdata -v /custom/mount:/var/lib/postgresql/data -d postgres
