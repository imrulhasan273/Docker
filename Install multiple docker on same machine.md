# **Install Multiple Docker on Same Machine**

---

## Install Centos on Docker (Master)

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

- Go to Master (`centOS`)

```shell
docker exec -it master bash # now I am in master (centos)
```

- Exit from `master`

```shell
exit
```

---

## Install Centos on Docker (Slave)

---

- Install CentOS

```shell
~$ docker pull centos:centos8
```

- Name the centOS as `Slave`

```shell
~$ docker run -d -t --name slave centos:centos8
```

- Check the docker container list

```shell
~$ docker ps
```

- Go to Slave (`centOS-8`)

```shell
docker exec -it slave bash # now I am in master (centos)
```

- Exit from `slave`

```shell
exit
```

---




