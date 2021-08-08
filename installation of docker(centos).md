# **Installation of Docker (CentOS)**

---

- [Ref](https://phoenixnap.com/kb/how-to-install-docker-centos-7)

---


## Step 1: Update Docker Package Database

```shell
sudo yum check-update
```

## Step 2: Install the Dependencies

```shell
sudo yum install -y yum-utils device-mapper-persistent-data lvm2
```

## Step 3: Add the Docker Repository to CentOS

```shell
sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
```

## Step 4: Install Docker On CentOS Using Yum

```shell
sudo yum install docker
```

## Step: 5 Manage Docker Service

1. Start Docker:

```shell
sudo systemctl start docker
```

2. Enable Docker:

```shell
sudo systemctl enable docker
```

3. Check the status of the service with

```shell
sudo systemctl status docker
```

---

