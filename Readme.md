# Containerization with docker fundamental

![docker image](docker.png)


## Docker Basic Command

**list of container running**

```bash
docker ps
```

**list of container all**

```bash
docker ps -a
```

**list of images**

```bash
docker image ls
```

**pull image**

```bash
docker pull image:tag
```

**run image**

```bash
docker run it --rm --name -p [port:port] [imagename]:[tag]
```

**remove image**

**tag version**

```bash
docker tag [old-image-name:tag] [new-image-name:tag]
```

**build image**

```bash
docker build -t [image-name:tag] ./path
```

**networks**

```bash
docker network ls
```

**login image repository**

```bash
docker login [urlrepo]
```
**push image**

```bash
docker push [repo/user/imagename:tag]
```

**list of volume**

```bash
docker volume ls
```
