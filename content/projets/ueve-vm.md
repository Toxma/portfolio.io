+++
title = "Création de VM à la demande"
date = 03/02/2022
menu = "main"
+++

![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white) ![Nutanix](https://img.shields.io/badge/nutanix-024DA1.svg?style=for-the-badge&logo=nutanix&logoColor=white) ![Jinja2](https://img.shields.io/badge/jinja2-B41717.svg?style=for-the-badge&logo=jinja&logoColor=white)

> J'ai réalisé ce projet lors de mon second stage de BTS. Le but était de créer une plateforme afin que les chercheurs de l'université d'Evry puissent avoir des VM provisionnées automatiquement de type stack LAMP. J'ai réalisé ce projet avec un autre stagiaire présent à ce moment et mon tuteur qui nous a supervisé pendant les 5 semaines de stage.
<!--more-->
---

- [Technologies utilisées](#technologies-utilisées)
  - [Nutanix](#nutanix)
  - [Cloud-init](#cloud-init)
  - [Jinja2](#jinja2)
  - [genisoimage](#genisoimage)
  - [Ansible](#ansible)
  - [Ansible Tower](#ansible-tower)

---

## Technologies utilisées

### Nutanix

- Hyperviseur de type 1 (bare metal)
- Infrastructure hyperconvergée

### Cloud-init

- Configuration du système d'exploitation au démarrage
  - Réseau
  - clé SSH
  - Utilisateurs
  - Mot de passe
- Fichier de configuration en yaml

### Jinja2

- Moteur de template en python
- Permet d'ajouter des variables ou des conditions dans un fichier
- Possible de l'éxecuter avec un fichier en JSON en entrée

### genisoimage

- Programme pour créer des images de systèmes de fichier
- Dans notre cas nous avons créer une image iso avec les fichiers cloud-init dedans

### Ansible

### Ansible Tower
