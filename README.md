# TP : Mise en place d'un Serveur DHCP sous Ubuntu

## Objectifs du travail
Ce TP a pour but d'installer et de configurer un serveur DHCP (ISC DHCP Server) capable de gérer plusieurs plages d'adresses sur un même sous-réseau. Les compétences visées sont :
- Configuration d'une adresse IP statique avec Netplan.
- Installation et paramétrage du service `isc-dhcp-server`.
- Définition de plages d'adresses multiples (multi-ranges).
- Analyse des baux (leases) et des logs.

## Technologies utilisées
- **OS** : Ubuntu Server (22.04 LTS).
- **Service** : ISC DHCP Server (`isc-dhcp-server`).
- **Réseau** : Netplan (YAML), `iproute2`.
- **Client** : `dhclient`.

## Contenu du dépôt
Ce dépôt contient :
1. **Rapport** : Documentation technique détaillée au format PDF (source LaTeX incluse).
2. **Configuration** : 
   - Fichier Netplan pour l'IP statique.
   - Fichier `dhcpd.conf` complet avec deux plages d'adresses et réservations.

## Instructions
1. **Génération du rapport** :
   Compilez le fichier `.tex` : `pdflatex rapport/rapport_dhcp.tex`.
2. **Déploiement** :
   Les fichiers du dossier `configuration/` sont destinés à être copiés respectivement dans `/etc/netplan/` et `/etc/dhcp/` sur le serveur.

## Membres du groupe
* [Ton Nom]
* [Nom du binôme]
