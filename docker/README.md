# DOCKER

### MYSQL (PERCONA) 

`docker volume create --name mypercona_data`

`docker volume create --name mypercona_logs`

`docker-compose -f infrastructure.yml up -d mypercona`

`docker exec -it <container_id> bash`

`mysql -u root -p`

