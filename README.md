# mobile-health-docker

## Docker image version

```
$ docker pull nginx:1.21.6
$ docker pull mysql:5.7
$ docker pull redis:6
$ docker pull nacos/nacos-server:v2.0.4
$ docker pull nacos/nacos-mysql:8.0.16
$ docker pull cike/sentinel-dashboard-docker:latest
$ docker pull seataio/seata-server:1.4.2
$ docker pull docker.elastic.co/elasticsearch/elasticsearch:7.16.3
$ docker pull docker.elastic.co/kibana/kibana:7.16.3
```

## Install

### First

```
$ git clone https://github.com/lostblackknight/mobile-health-docker.git
```

### Second

```
$ cd mobile-health-docker/elasticsearch
$ cd mobile-health-docker/nacos
$ cd mobile-health-docker/nginx
$ cd mobile-health-docker/redis
$ cd mobile-health-docker/seata-server
$ cd mobile-health-docker/sentinel-dashboard
```

### Third

```
$ docker compose up -d
$ docker compose up
```

- `-d` run the container in detached mode (in the background)

## Docker command references

```
$ docker ps
$ docker ps -a

$ docker images
$ docker image rm <image-id>

$ docker rm -f <container-id>
$ docker cp <container-id>:/container/path /your/path
$ docker exec -it <container-id> /bin/bash
```
