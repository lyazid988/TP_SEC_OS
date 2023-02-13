# TP SEC OS

## Nmap avec conteneur Docker

[![cd](https://github.com/jonlabelle/docker-nmap/actions/workflows/cd.yml/badge.svg)](https://github.com/jonlabelle/docker-nmap/actions/workflows/cd.yml)
[![docker pulls](https://img.shields.io/docker/pulls/jonlabelle/nmap?label=docker%20pulls)](https://hub.docker.com/r/jonlabelle/nmap)
[![image size](https://img.shields.io/docker/image-size/jonlabelle/nmap/latest?label=image%20size)](https://hub.docker.com/r/jonlabelle/nmap/tags)

Nmap est un scanner de ports libre créé par Fyodor et distribué par Insecure.org. Il est conçu pour détecter les ports ouverts, identifier les services hébergés et obtenir des informations sur le système d'exploitation d'un ordinateur distant. Ce logiciel est devenu une référence pour les administrateurs réseaux car l'audit des résultats de Nmap fournit des indications sur la sécurité d'un réseau. Il est disponible sous Windows, Mac OS X, Linux, BSD et Solaris.

L'idée du TP sera donc d'installer docker sur un environnement linux, et de pouvoir run nmap dans un conteneur docker

## étape 1 : installation et test de fonctionnement de docker
<img src='docker run.png'>

## étape 2:
J'ai git clone le repo intrumentisto contenant la config nmap pour docker et je le run comme ci dessous :
```bash
docker run [docker run options ...] instrumentisto/nmap [nmap options ...] <nmap target(s)>
```

## Exemple

j'ai tester de lancer une commande nmap pour scanner une adresse vulnerable fournie par le prof de sécurité réseaux
<img src=nmap.png>


## Chiffrement de conteneur
### Installation VeraCrypt sur debian 11:
```bash
wget https://launchpad.net/veracrypt/trunk/1.25.9/+download/veracrypt-1.25.9-Debian-11-amd64.deb

sudo apt install ./veracrypt-1.25.9-Debian-11-amd64.deb -y
```


### Chiffrer quelques répertoires 
### Créer un container chiffré de 1Mo
