# **Installation of Docker (CentOS)**

---

- [Ref](https://phoenixnap.com/kb/how-to-install-docker-centos-7)

---


## Step 1: Update Docker Package Database

```shell
root~$ sudo yum check-update
```

---

## Step 2: Install the Dependencies

```shell
root~$ sudo yum install -y yum-utils device-mapper-persistent-data lvm2
```

---

## Step 3: Add the Docker Repository to CentOS

```shell
root~$ sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
```

---

## Step 4: Install Docker On CentOS Using Yum

```shell
root~$ sudo yum install docker
```

---

## Step: 5 Manage Docker Service

1. Start Docker:

```shell
root~$ sudo systemctl start docker
```

2. Enable Docker:

```shell
root~$ sudo systemctl enable docker
```

3. Check the status of the service with

```shell
root~$ sudo systemctl status docker
```

---

# **Install a Specific Version of Docker on CentOS**

---

```shell
yum list docker-ce --showduplicates | sort –r
```

> The system should give you a list of different versions from the repositories you have enabled above.


```shell
sudo yum install docker-ce-<VERSION STRING>
```

---

