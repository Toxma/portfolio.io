+++
title = "Homelab"
date = 2023-01-25
menu = "main"
+++
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)![Podman](https://img.shields.io/badge/podman-%235835CC.svg?style=for-the-badge&logo=podman&logoColor=white)![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white)
> Depuis maintenant 3 mois j'essaye de me construire mon propre homelab afin de pouvoir pratiquer des technologies et ainsi m'autoformer. Ceci permet également d'ajouter un côté pratique à tout ce que j'apprend en ligne, en cours, etc.

<!--more-->
---

- [Mon infrastructure](#mon-infrastructure)
- [Mes services](#mes-services)
  - [Portainer](#portainer)
  - [FreshRSS](#freshrss)
  - [Prometheus / Grafana](#prometheus--grafana)
  - [PiVPN (Wireguard)](#pivpn-wireguard)
- [Par la suite](#par-la-suite)

---

## Mon infrastructure

---

- Raspberry Pi 4 4GB
- NAS Synology DS214
- Switch Netgear 8 ports 1Gb/s

## Mes services

---

> Actuellement j'héberge 4 services sur mon Raspberry PI, 3 services conteneurisé avec docker et le dernier (VPN) installé directement sur le Raspberry PI. Les services conteneurisés sont déployés grâce à des fichiers docker-compose ce qui permet une configuration et un déploiement rapide.

### Portainer

- Gestion des containers depuis une interface web

### FreshRSS

- Agrégateur de flux RSS
- Permet de faire ma veille technologique

### Prometheus / Grafana

- Permet de superviser mon raspberry pi
- Avoir un dashboard accessible depuis le web

### PiVPN (Wireguard)

- VPN me permettant d'accéder à mon homelab depuis n'importe où

---

## Par la suite

---

> Prochainement je souhaiterai m'acheter ou bien récupérer des composants afin de pouvoir améliorer mon infra et me faire un serveur plus puissant. Ceci permettrait d'installer un hyperviseur de type 1 comme proxmox dessus.
