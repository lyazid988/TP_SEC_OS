# TP SEC OS : Nmap avec conteneur Docker

[![cd](https://github.com/jonlabelle/docker-nmap/actions/workflows/cd.yml/badge.svg)](https://github.com/jonlabelle/docker-nmap/actions/workflows/cd.yml)
[![docker pulls](https://img.shields.io/docker/pulls/jonlabelle/nmap?label=docker%20pulls)](https://hub.docker.com/r/jonlabelle/nmap)
[![image size](https://img.shields.io/docker/image-size/jonlabelle/nmap/latest?label=image%20size)](https://hub.docker.com/r/jonlabelle/nmap/tags)

## étape 1 : installation et test de fonctionnement de docker
<img src='docker run.png'>

## étape 2:
J'ai git clone un repo de docker-nmap et je le run comme ci dessous :
```bash
docker run [docker run options ...] instrumentisto/nmap [nmap options ...] <nmap target(s)>
```

## Exemple

j'ai tester de lancer une commande nmap pour scanner une adresse vulnerable fournie par le prof de sécurité réseaux
<img src=nmap.png>


