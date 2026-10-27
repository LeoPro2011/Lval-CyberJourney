# Léo Val — Parcours en cybersécurité

> Étudiant en cybersécurité, orienté fondamentaux réseau, investigation défensive, IA appliquée à la cybersécurité et compréhension des outils offensifs.

🇫🇷 Français | [🇬🇧 English](README.en.md)

## Profil actuel

Je suis Léo Val, étudiant, et je documente mon parcours en cybersécurité depuis mi-août 2026.

Mon orientation est en cours d'exploration : je veux consolider le réseau et les outils de cybersécurité tout en étudiant l'**IA appliquée à la cybersécurité**, le cloud, le SOC et le DFIR. Je ne m'engage pas encore exclusivement dans le pentest offensif.

J'apprends principalement à travers des labs pratiques, des environnements de type CTF, des formations structurées et des projets personnels.

## Ce que je connais et pratique actuellement

### Sécurité offensive
- Fondamentaux du reverse engineering : `strings`, `xxd`, `checksec`, Ghidra, analyse statique, premiers pas avec GDB et exécution symbolique
- Reconnaissance passive et OSINT de base
- Méthodologie et éthique du pentest
- Reconnaissance et énumération
- Nmap
- Dirb
- Hydra
- Metasploit / msfconsole
- Tests d'applications web
- Énumération de sous-domaines
- Tests d'authentification
- Manipulation de JWT et de cookies
- Élévation de privilèges sous Linux
- Reverse shells dans des environnements de lab autorisés
- Exploitation basique et enchaînement de vulnérabilités
- Énumération et exploitation de services réseau dans des labs autorisés
- Fondamentaux de SMB, FTP et Telnet

### Fondamentaux
- WHOIS, DNS, `nslookup` et `dig`
- ASN et infrastructure réseau
- Fondamentaux réseau
- Concepts LAN
- DNS
- HTTP
- Fondamentaux des applications web
- Fondamentaux des systèmes d'exploitation
- Bases de Linux et Windows
- Représentation et encodage des données
- Fondamentaux de la cryptographie
- CIA Triad
- Bases du DFIR et des concepts SOC

### Sécurité de l'IA
- Fondamentaux de l'IA/ML/LLM
- Prompt engineering
- Concepts de sécurité des LLM
- Modélisation des menaces appliquée à l'IA
- Menaces liées à la sécurité de l'IA
- Concepts d'adversarial prompting

### Environnement et développement
- Kali Linux
- Ubuntu
- WSL
- Machines virtuelles
- Git / GitHub
- Développement assisté par IA et vibe coding

## TryHackMe

État au 21 octobre 2026 (déclaré par moi) : **Capability Score : 47**, **top 5 % mondial**, **44e en France au classement mensuel**, **1er de la ligue Ruby**, **streak : 21 jours** ; **8 600 points** ; **rang Mage**. Le nombre total de rooms et le rang mondial all-time ne sont pas actualisés faute de chiffres récents confirmés.

Dernier suivi (20 octobre 2026) : **44e en France au classement mensuel** ; **top 5 % mondial** ; **1er de la ligue Ruby** ; **Capability Score : 47** ; **streak : 21 jours**. Statistiques déclarées par moi.

Profil : https://tryhackme.com/p/leo.valpro1903

Mes rooms terminées couvrent le réseau, Linux, la sécurité web, la reconnaissance, le pentest, l'exploitation, la sécurité défensive, le DFIR et la sécurité de l'IA. AI Forensics est terminée depuis le 14 octobre.

## Journal d'apprentissage

Les journaux datés sont archivés dans [`2026/10-2026/`](2026/10-2026/) et le récapitulatif mensuel bilingue est disponible dans [`journey/2026/10-2026.md`](journey/2026/10-2026.md) et [`journey/2026/10-2026.en.md`](journey/2026/10-2026.en.md). Les journées sans pratique ne sont pas comptées comme des rooms terminées.





### 26 octobre 2026 — Première découverte de PowerShell

Poursuite de **Cybersecurity 101** avec une première exploration de Windows PowerShell : recherche et consultation de l'aide pour repérer les commandes disponibles. Découverte utile pour les bases IT et le helpdesk, sans prétendre maîtriser l'outil.

Journal détaillé : [journal du 26 octobre](2026/10-2026/2026-10-26.md).

### 24 octobre 2026 — Windows Command Line et PHP2Shell

Room **Windows Command Line** terminée. Découverte d'un exploit Python associé à l'ASLR dans un lab volontairement vulnérable ; le mécanisme de contournement reste à approfondir.

Journal détaillé : [journal du 24 octobre](2026/10-2026/2026-10-24.md).

### 23 octobre 2026 — Active Directory

J'ai terminé une room TryHackMe sur l'organisation d'Active Directory, les stratégies de groupe (GPO), l'authentification Kerberos et NetNTLM, ainsi que les domaines, arbres, forêts et relations d'approbation (*trusts*).

Journal détaillé : [journal du 23 octobre](2026/10-2026/2026-10-23.md).

### 22 octobre 2026 — Vulnérabilité PHP et Active Directory

J'ai découvert les bases d'Active Directory et terminé une room TryHackMe consacrée à une vulnérabilité PHP. J'ai étudié `session.upload_progress`, le traitement des requêtes multipart avant l'exécution du script, ainsi qu'un problème de gestion mémoire lié au *bailout* et à `longjmp`. La classification CWE reste à vérifier : CWE-824 concerne un pointeur non initialisé, tandis que CWE-416 vise l'utilisation après libération.

Journal détaillé : [journal du 22 octobre](2026/10-2026/2026-10-22.md).

### 21 octobre 2026 — Windows Fundamentals 3

J'ai terminé [Windows Fundamentals 3](https://tryhackme.com/room/windowsfundamentals3x0x), qui approfondit les fonctionnalités de sécurité intégrées à Windows. Cette room poursuit la consolidation de mes bases Windows dans le parcours Cybersecurity 101.

Journal détaillé : [journal du 21 octobre](2026/10-2026/2026-10-21.md).

### 20 octobre 2026 — TryHackMe et Cisco Packet Tracer

J'ai terminé [Windows Fundamentals 2](https://tryhackme.com/room/windowsfundamentals2x0x), en approfondissant Task Manager, UAC, System Configuration (`msconfig`) et les paramètres système avancés. J'ai aussi découvert des outils d'administration et de diagnostic comme Computer Management, Task Scheduler, Event Viewer, System Information, Resource Monitor et Registry Editor.

J'ai également terminé l'activité **Tutored Exploration — Logical and Physical Mode** de Cisco Packet Tracer, puis terminé la formation **Cisco Packet Tracer** et obtenu le certificat associé. J'ai trouvé la simulation particulièrement intéressante et réaliste : elle permet de manipuler les modes logique et physique et de renforcer une vision globale des réseaux.

Le parcours **Cisco Junior Cybersecurity Analyst** est très long ; je le traiterai comme un **projet parallèle sur l'année scolaire**, plutôt que comme une priorité à terminer rapidement. Il doit me permettre de construire une base générale solide en systèmes, réseaux et cybersécurité.

Journal détaillé : [journal du 20 octobre](2026/10-2026/2026-10-20.md).

### 19 octobre 2026 — TryHackMe

Quatre rooms terminées :
- [Windows Fundamentals 1](https://tryhackme.com/room/windowsfundamentals1xbx) — aperçu des composants et outils Windows. Contenu introductif, mais utile pour reconnaître les fonctions système et mieux comprendre les postes Windows en entreprise.
- [Lo-Fi](https://tryhackme.com/room/lofi) — exercice pratique de navigation dans le système de fichiers Linux pour retrouver un flag à la racine de la machine.
- [W1seGuy](https://tryhackme.com/room/w1seguy) — challenge de cryptographie centré sur l'analyse d'un mécanisme de chiffrement et la récupération du message/flag.
- [Light](https://tryhackme.com/room/lightroom) — exploitation d'une injection SQL dans une application web ; apprentissage du risque lié à l'intégration non sécurisée des entrées utilisateur dans une requête SQL.

Cette journée a consolidé des notions de systèmes et de sécurité web. L'injection SQL de Light fait le lien avec les bases SQL travaillées dans Pre Security.

## Formations actuelles

- **TryHackMe — Pre Security :** terminé à **100 % le 18 octobre 2026**. Le parcours a consolidé les fondamentaux réseau, systèmes, Linux et Windows, bases de données/SQL, cloud, virtualisation et sécurité des systèmes d'exploitation. Les démonstrations Python et JavaScript étaient surtout des révisions introductives.

- **Networking :** étude des fondamentaux réseau et de l'analyse réseau via TryHackMe. Abonnement annuel Premium désormais actif pour utiliser l'AttackBox et suivre des learning paths complets.
- **Network Services :** terminée le 3 octobre 2026, avec de la pratique sur l'énumération/exploitation de SMB, Telnet et FTP dans un lab autorisé.
- **Network Services 2 :** terminée le 6 octobre 2026, avec une première pratique de NFS, SSH, SUID, SMTP, Postfix et MySQL dans un lab autorisé.
- **Network Reconnaissance :** module actuellement en cours, en commençant par la reconnaissance passive.
- **WiFi Fundamentals and Recon :** terminée le 11 octobre. Je connais et j'ai déjà exécuté le protocole de reconnaissance Wi-Fi en lab (mode monitor, scan multibande, analyse des réseaux/stations, découverte d'un SSID masqué). Compétence pratiquée mais pas encore maîtrisée complètement ; je dois encore gagner en autonomie et en régularité.
- **Red Queen (TryHackMe) :** analyse simple et statique terminées ; découverte de `xxd`, `checksec`, `strings`, Ghidra et du décodage XOR. Analyse dynamique avec GDB puis introduction à l'exécution symbolique avec `angr` et les contraintes SMT/Z3. Room toujours en cours.
- **Web Hacking 1 :** mis en attente car une grande partie du contenu actuellement proposé nécessite un abonnement payant.
- **Cisco Networking Academy — Introduction à la cybersécurité :** **certification obtenue le 5 octobre 2026** ; examen final réussi avec **73 %**.
- **Cisco Packet Tracer :** formation terminée le **20 octobre 2026**, certificat obtenu. L'activité Tutored Exploration — Logical and Physical Mode a renforcé ma compréhension de la représentation logique et physique d'un réseau.
- **TryHackMe — AI Forensics :** terminée le 14 octobre 2026 ; pratique guidée de reconstruction de timeline, corrélation d'artefacts, détection d'anomalies par IA et analyse des faux positifs.
- **TryHackMe — Health Hazard :** room et entraînement pratique terminés en octobre 2026 ; approfondissement du Threat Hunting et de l'investigation à partir de logs.
- **TryHackMe — OWASP Top 10 2025: IAAA Failures :** terminée le 14 octobre 2026 ; étude des défaillances liées à l'identité, l'authentification, l'autorisation et l'audit. À consolider par des exercices autonomes de contrôle d'accès.
- **Orientation en exploration :** IA et cybersécurité, cloud/réseau, SOC et DFIR ; poursuite de l'apprentissage des outils offensifs sans engagement définitif dans le pentest.
- **Harvard CS50's Introduction to Cybersecurity :** prochaine formation de fond, avec un objectif d'environ **30 minutes par jour**.

Je veux encore réviser les sept couches OSI avant d'aller plus loin dans le réseau.

## Certifications et prochaine étape

- **Cisco Networking Academy — Introduction à la cybersécurité** — certificat de fin de cours obtenu le **5 octobre 2026** ; examen final réussi avec **73 %**.
- **Cisco Junior Cybersecurity Analyst learning path :** projet parallèle prévu sur l'année scolaire, car le parcours est très long. Il s'inscrit dans une stratégie de consolidation progressive des fondamentaux plutôt que dans une course à la certification.
- **Piste à évaluer : Cisco CCST Cybersecurity**, certification professionnelle distincte d'un certificat de fin de cours ; contenu, prérequis et coût à vérifier avant décision.

## Projets

### VulnScope

VulnScope est un scanner expérimental de sécurité web développé comme projet d'apprentissage et de portfolio en cybersécurité.

Le projet a notamment impliqué du crawling, de la reconnaissance, du profilage technologique, de la détection d'en-têtes de sécurité, de la détection de vulnérabilités, du reporting, de l'analyse CORS, de la corrélation CVE et des tests automatisés.

Le projet est destiné aux tests de sécurité autorisés.

### Autres développements

J'ai également développé plusieurs projets SaaS avec des outils de développement assisté par IA, dont une première plateforme personnalisée d'apprentissage de la cybersécurité.

## Parcours

J'ai commencé à apprendre la cybersécurité à la mi-août 2026. J'ai d'abord appris en réalisant des rooms TryHackMe, puis j'ai progressivement construit des connaissances pratiques en résolvant des challenges.

Depuis, mon orientation s'est de plus en plus concentrée sur la sécurité offensive, le pentest web et infrastructure, la post-exploitation Linux et la sécurité de l'IA.

Ce repository documente cette progression à travers des journaux datés, des projets, des labs et des preuves de pratique.

## Direction actuelle

**Fondamentaux réseau → pratique défensive et investigation (SOC/DFIR) → IA appliquée à la cybersécurité / cloud / réseau**, tout en continuant à apprendre les outils offensifs. Cette trajectoire reste exploratoire.

Il s'agit d'une trajectoire d'apprentissage, et non d'une revendication d'expertise professionnelle.

## Principe du portfolio

Je veux que ce repository montre ce que j'ai réellement pratiqué, et pas uniquement les technologies dont j'ai entendu parler.

Lorsque c'est possible, les compétences sont accompagnées de labs, projets, expériences, write-ups, code ou autres éléments de preuve.

---

*Toutes les pratiques de sécurité offensive documentées ici sont destinées à des environnements autorisés.*
