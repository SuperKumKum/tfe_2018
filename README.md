# tfe_2018
## Mise en place du serveur VPS 
> Adresse: **51.254.205.113** ou **vps510877.ovh.net**
## Création d'un utilisateur sans droits root (pour éviter d'effectuer des actions non voulues sur le système).
## Mise en place sécurité (connexion) 
- Désactivation de la connexion avec l'utilisateur root 
- Activation de l'authentification par clé
- Génération d'une clé publique et privée asymétrique avec Putty + ajout d'un paraphrase
- Désactivation de la connexion par mot de passe
- Modificaiton du port par défaut ssh (22) par un autre port pour éviter des attaques brute-force sur ce port. (Remplacé par le port 22022)
## Mise en place de sécurité (Firewall)
Utilisation du service iptables de Linux installé de base sur le système permettant la gestion des paquets passant sur le serveur. Mise en place de règles basées sur les ports utilisés.
> Script security.sh
