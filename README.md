<div align="center"> 

# Catálogo Docker Compose


![Static Badge](https://img.shields.io/badge/docker-gray?style=for-the-badge&logo=docker)


</div>


## Objetivo

Esse repositório é o que eu uso para versionar as stacks que eu mais utilizo para estudo e testes, quer usar como base



## Script para Limpar seu docker

```
#!/bin/bash

docker container rm -f $(docker container ls -qa)
docker image rm -f $(docker image ls -q)
docker network rm -f $(docker network ls -q)
docker volume rm -f $(docker volume ls -q)
docker system prune --all --force`

```
