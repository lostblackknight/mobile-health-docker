# mobile-health-docker

## 安装

### 第一步

```
git clone https://github.com/lostblackknight/mobile-health-docker.git
```

### 第二步

```
cd mobile-health-docker/nginx
cd mobile-health-docker/nacos
cd mobile-health-docker/sentinel-dashboard
cd mobile-health-docker/seata-server
cd mobile-health-docker/redis
```

### 第三步

```
docker compose up -d
docker compose up
```

### 第四步

```
docker ps
docker ps -a
docker images
docker exec -it <container-id> /bin/bash
docker cp <container-id>:/container/data /data
docker rm -f <container-id>
docker image rm <image-id>
```
