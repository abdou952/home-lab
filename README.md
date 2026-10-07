# home-lab
document my home lab journey (selfhost, network security and automation)

ansible automation server-- sudo apt upgrade, clean etc into every VM

VLAN 2 :
Administration d'un Serveur Physique On-Premise
2025 – Présent Auto-hébergement · Docker · SSH · Sécurité
Déploiement de services via Docker Compose sur réseau isolé, avec reverse proxy Nginx et certificats SSL/TLS.
Audit de sécurité Nmap/Nessus : réduction de la surface d'attaque et correction des vulnérabilités.
Supervision avec Uptime Kuma (HTTP, DNS, TCP) et détection d'intrusions via Crowdsec.



VLAN 1 :
Virtualisation et Infrastructure Réseau sous Proxmox VE
2026 Proxmox · pfSense · Windows Server · Active Directory · Debian · Jira · GitHub
Segmentation et virtualisation d'un réseau privé via implémentation d'un firewall pfSense (interfaces WAN/LAN, règles de filtrage).
Déploiement d'un VPN (OpenVPN) pour sécuriser le réseau LAN et contrôler les accès externes.
Simulation d'un environnement d'entreprise : Windows Server
(DHCP, DNS, GPO), Active Directory, clients Windows/Linux multi-profils.
Intégration de Jira (ticketing/gestion des incidents) et rédaction d'une documentation technique sur GitHub.


VLAN 10, Self-host (Docker): Debian Docker VM with Nginx, Uptime Kuma, CrowdSec and your other services. Example subnet: 10.0.10.0/24.
VLAN 20, Company: AD domain controller, the two Windows VMs, and the Linux client. Example subnet: 10.0.20.0/24.

