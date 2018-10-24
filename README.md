# docker commands

## Docker Start
docker-compose up -d

## Docker Stop
docker-compose stop

docker stop CONTAINER_ID

## List Images
docker images -a

## Remove one image
docker rmi Image

## Remove ALL images
docker rmi $(docker images -a -q)

## List Containers
docker ps -a

## Remove Containers
docker rm CONTAINER_ID_1 CONTAINER_ID_2 ...

## Access Container
docker exec -it CONTAINER_ID bash

## Build Docker Image
docker build -t IMAGE_NAME .


## References
https://tableless.com.br/iniciando-com-o-docker-criando-suas-proprias-imagens/

https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes
