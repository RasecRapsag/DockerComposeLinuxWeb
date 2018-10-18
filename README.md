# Docker Compose Linux na Web
Exemplos Docker Compose


## Introdução

Para criação dos ambientes, será necessário que o Docker e o Docker Compose estejam instalados no sistema Linux.


### Instalação Docker

```bash
$ sudo curl -fsSl https://get.docker.com | bash
$ sudo usermod -aG docker $(whoami)
```


### Instalação Docker Compose

```bash
$ sudo curl -L https://github.com/docker/compose/releases/download/1.17.0/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
$ sudo chmod 755 /usr/local/bin/docker-compose
```


### Clonando repositório

```bash
$ mkdir ~/Dockers && cd ~/Dockers
$ git clone https://github.com/RasecRapsag/DockerComposeLinuxWeb
```
