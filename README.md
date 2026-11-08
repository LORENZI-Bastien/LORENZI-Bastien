<h1 align="center">Bastien Lorenzi</h1>

<p align="center">
  <strong>Étudiant en 3<sup>e</sup> année de BUT Réseaux et Télécommunications · parcours cybersécurité</strong><br>
  Montbéliard · Technicien en alternance chez <strong>Scutum</strong>, à Rixheim
</p>

<p align="center">
  <a href="https://bastien-lorenzi.netlify.app/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-Visiter-a78bfa?style=for-the-badge&logo=netlify&logoColor=white"></a>
  <a href="mailto:bastienlorenzi70@gmail.com"><img alt="E-mail" src="https://img.shields.io/badge/E--mail-Me%20contacter-1a1526?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

### 👋 En bref

- 🎓 BUT Réseaux et Télécommunications, **parcours cybersécurité**, à Montbéliard
- 🛡️ Technicien en alternance chez **Scutum** (vidéosurveillance, contrôle d’accès, anti-intrusion, sécurité incendie, télésurveillance)
- 🎯 Après le BUT : entrer dans la vie active comme **technicien**. Mon alternance m’a confirmé que j’apprécie le terrain et le contact avec les clients.

### 🔧 Sur le terrain

`SAV` · `Installation de matériel` · `Configuration du système` · `Formation du client`

### 🧰 Outils et notions pratiqués

| Domaine | Outils |
|---|---|
| Réseaux | Adressage IP, VLAN, DHCP, SSH, NFS / Samba, Wireshark, Cisco |
| Cybersécurité | Stormshield, NAT / filtrage, Snort, Kali Linux, Nmap, Nessus, Metasploit, Burp Suite, Root-Me |
| Télécoms | Wi-Fi, antennes, VoIP, FreePBX, Linphone, GNU Radio |
| Systèmes & dev | Linux, Raspberry Pi, Docker / Compose, WSL2, Tailscale, Python / Flask, SQLite, Arduino / C++, HTML / CSS |

### 🏠 Mon homelab

Une petite infrastructure montée chez moi sur du matériel de récupération, accessible uniquement par VPN, **sans aucun port ouvert sur la box**. Le Raspberry Pi tourne 24 h/24 pour les services légers ; la tour, plus gourmande, est réveillée à la demande pour l’IA locale et les tâches lourdes.

| Machine | Rôle | Services |
|---|---|---|
| Raspberry Pi 5 (8 Go, SSD NVMe) · Raspberry Pi OS, Docker | Serveur 24 h/24 (~2,3 Go de RAM sur 8) | AdGuard Home (DNS du réseau, DoH), Vaultwarden, Radicale, Immich, n8n, Uptime Kuma, point politique quotidien |
| Tour (Ryzen 5 1600, 16 Go, GTX 1660 Super) · Windows 10, WSL2, Docker | Puissance à la demande | Ollama + Open WebUI (IA locale sur GPU), Jellyfin, Navidrome, reconnaissance de visages et sauvegarde le soir ; Home Assistant et Homepage en cours de bascule vers le Pi |

- 🗳️ **Projet maison** : [point politique quotidien](https://github.com/LORENZI-Bastien/portfolio/tree/main/outils/point-politique), un service Python sans dépendance sur le Pi qui lit les données ouvertes de l’Assemblée nationale, du Sénat et de vie-publique et publie chaque matin un résumé neutre des votes sur Discord (10 tests unitaires)
- 🔐 **Accès** : Tailscale (WireGuard) avec MagicDNS, `tailscale serve` comme reverse proxy et certificats Let’s Encrypt
- 🧱 **Sécurité** : ports des conteneurs liés à la machine locale, pare-feu sur chaque hôte, SSH par clé, mises à jour automatiques, secrets hors du code, inscriptions fermées sur le gestionnaire de mots de passe
- 💾 **Continuité** : sauvegardes versionnées (rsync + dumps des bases) plutôt qu’un RAID, migrations vérifiées par SHA256. Point faible actuel : le disque de sauvegarde a lâché, pas encore de sauvegarde automatique valide
- 🚧 **En cours** : nouveau disque et première sauvegarde complète vérifiée, déplacement des services restants et des téléphones vers le Pi, double authentification du gestionnaire de mots de passe
- 🗺️ **Prévu** : Ethernet et Wake-on-LAN de la tour depuis le Pi (à la demande et chaque soir), ACL Tailscale, Prometheus et Grafana, labo Kubernetes (k3s)

### 📂 Mes projets de BUT (SAÉ)

| SAÉ | Projet | Thème |
|---|---|---|
| 4.Cyber.01 | [Sécuriser un système d’information](https://github.com/LORENZI-Bastien/SAE-4.Cyber.01-Securiser-SI) | Pare-feu Stormshield, DMZ, Snort |
| 3.04 | [Découvrir le pentesting](https://github.com/LORENZI-Bastien/SAE-3.04-Pentesting) | Root-Me, Burp Suite, analyse de journaux |
| 2.4 | [Auditer un environnement de test](https://github.com/LORENZI-Bastien/SAE-2.4-Projet-integratif) | Kali, Nmap / Nessus, Metasploit |
| 2.3 | [Le ventilomètre](https://github.com/LORENZI-Bastien/SAE-2.3-Ventilometre) | Python / Flask, SQLite, API météo |
| 2.2 | [Mesurer un signal en téléphonie VoIP](https://github.com/LORENZI-Bastien/SAE-2.2-Mesure-de-signaux) | FreePBX, Linphone, GNU Radio |
| 2.1 | [Construire un réseau pour une petite structure](https://github.com/LORENZI-Bastien/SAE-2.1-Infrastructure-reseau) | DHCP, VLAN, SSH, Linux |
| 1.5 | [Robot suiveur de ligne](https://github.com/LORENZI-Bastien/SAE-1.5-Robot-suiveur-de-ligne) | Arduino, C++ |
| 1.4 | [Se présenter sur Internet](https://github.com/LORENZI-Bastien/SAE-1.4-Site-web) | HTML / CSS |
| 1.3 | [Découvrir un dispositif de transmission](https://github.com/LORENZI-Bastien/SAE-1.3-Dispositif-transmission) | Wi-Fi, antennes |
| 1.2 | [S’initier aux réseaux informatiques](https://github.com/LORENZI-Bastien/SAE-1.2-Reseaux-informatiques) | Wireshark, SSH, Nmap |
| 1.1 | [Hygiène numérique](https://github.com/LORENZI-Bastien/SAE-1.1-Hygiene-numerique) | Cisco Networking Basics |

### 🏐 En dehors du travail

**Handball** au HBC Lure Villers depuis l’âge de 9 ans · **Photographie** de paysages et de couchers de soleil · **Voyages** pour découvrir d’autres paysages et cultures.

---

<p align="center">
  📫 <a href="mailto:bastienlorenzi70@gmail.com">bastienlorenzi70@gmail.com</a> · 🌐 <a href="https://bastien-lorenzi.netlify.app/">Mon portfolio</a>
</p>
