

## To build docker image
docker build -t nodehelloworld .

## To list docker images
docker images

## To run docker containers
docker run -d -p 3030:3030 --name nodehelloworld nodehelloworld

## To list docker containers
docker ps

## To Get nodehelloworld logs
docker logs nodehelloworld

## To Stop nodehelloworld
docker stop nodehelloworld

## To Start nodehelloworld
docker start nodehelloworld

## To Remove Container
docker rm nodehelloworld