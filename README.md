# Dockerization

## Create Docker image

docker build -t web .

## Inspect Docker image

docker image inspect web

## Run container

docker run -p 8080:80 web

## Check containers status

docker ps
