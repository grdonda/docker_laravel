# docker com laravel e banco de dados postgres com pgadmin


## docker comandos
```shell
# subir a maquina e limpar excessos
docker-compose -f "docker-compose.yaml" up -d --build --remove-orphans

# desligar e limpar excessos
docker-compose down --remove-orphans

# limpeza de excessos
docker network prune --force
docker image prune --force
docker volume prune --force
```