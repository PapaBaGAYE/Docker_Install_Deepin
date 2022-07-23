# Docker_Install_Deepin

```
sudo apt update
```

```
sudo apt install apt-transport-https ca-certificates gnupg2 curl software-properties-common
```

```
sudo curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -
```

```
sudo apt-key fingerprint 0EBFCD88
```

```
printf 'deb [arch=amd64] https://download.docker.com/linux/debian buster stable\n'| sudo tee /etc/apt/sources.list.d/docker-ce.list
```

```
sudo apt-get update
```

```
sudo apt-get install docker-ce
```

```
docker --version
```


