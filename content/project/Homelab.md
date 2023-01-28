+++
title = "Homelab"
date = 2023-01-25T20:01:13+01:00
menu = "main"
+++

> Depuis maintenant 3 mois j'essaye de me construire mon propre homelab afin de pouvoir pratiquer des technologies et ainsi m'autoformer. Ceci permet également d'ajouter un coté pratique à tout ce que j'apprend en ligne, en cours, etc.

<!--more-->
---

## Mon infrastructure

- Raspberry Pi 4 4GB
- NAS Synology DS214
- Switch Netgear 8 ports 1Gb/s

---

## Mes services

> Actuellement j'héberge 4 services sur mon Raspeberry PI, 3 services conteneurisé avec docker et le dernier (VPN) installé directement sur le Raspeberry PI. Les services conteneurisé sont déployés grâce à des fichiers docker-compose ce qui permet une configuration et un déploiement rapide.

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

> Prochainement je souhaiterai m'acheter ou bien récupérer des composants afin de pouvoir améliorer mon infra et me faire un serveur plus puissant. Ceci permettrai d'installer un hyperviseur de type 1 comme proxmox dessus.
