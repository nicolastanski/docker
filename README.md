# docker commands

## Docker Start
docker-compose up -d

## Docker Stop
docker-compose stop


## List Images
docker images -a

## Remove one image
docker rmi Image

## Remove ALL images
docker rmi $(docker images -a -q)

## List Containers
docker ps -a

## Remove Containers
docker rm ID_or_Name ID_or_Name

## Access Container
docker exec -it CONTAINER_ID bash


https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes
