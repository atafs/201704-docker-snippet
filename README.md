# 201704-docker-snippet £££
docker commands

## Commands £££
docker-machine create --driver=virtualbox americo.docker

docker-machine env americo.docker

eval $(docker-machine env americo.docker)

docker build -f Dockerfile.nginx -t cubic:CUB-268 .

docker run -d -p 80:80 cubic:CUB-268

docker-machine ip americo.dev

docker-machine stop americo.docker

docker-machine start americo.docker

docker ps

docker images

docker kill <ps-number>

curl $(docker-machine ip americo.docker)

## tutorials £££
https://docs.docker.com/machine/get-started/

https://penandpants.com/2014/03/09/docker-via-homebrew/
