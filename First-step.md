# Install Docker

Windows :
[Follow this link](https://www.docker.com/get-started)

Linux : 
```bash
sudo apt-get install docker.io
```

# Fisrt step with CLI

List all runnings containers (processus) :
```bash
docker ps
```
>You can add `-a` to show all the container even the stopped one's

Run a container (You can import images form [DockerHub](https://hub.docker.com/)):
``` bash
docker pull alpine

docker -di --name fstuto run alpine:latest # OS:version
```

>You can do a `docker ps` to see the container you created

Connect to container
``` bash
docker exec -ti fstuto sh 
```

Stop container :
```bash
docker stop fstuto
```
