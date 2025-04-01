## Instalar docker
    sudo apt-get update && sudo apt install docker -y
Instalar docker compose

    sudo apt install docker-compose



## Instalar portainer
> Sirve para administrar los contenedores de docker o incluso stacks

Requisitos previos:

    mkdir -p /srv/docker/managment
    nano /srv/docker/managment/docker-compose.yml
    
    
    cd /srv/docker/managment
    docker-compose up -d
