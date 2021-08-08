# **Install Multiple Docker on Same Machine**

---

## Install Centos on Docker

---

- Install CentOS

```shell
~$ docker pull centOS
```

- Name the centOS as `Master`

```shell
~$ docker run -d -t --name master centos
```

- Check the docker container list

```shell
~$ docker ps
```

- Go to `centos`

```shell
docker exec -it master
```

---



