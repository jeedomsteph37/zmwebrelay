# ZmWebRelay 

Le plugin sert à gérer la carte ZmWebRelay 5.2
Il permet de piloter les 8 relais en mode impulsion ou normal et de récupérer les états numériques presque en temps réels.  

Ce plugin utilise les 2 modes de communications avec la carte : socket et Web.
Toutes les commandes sont envoyées directement en Web et tous les retours d'informations sont récupérés par le port 1234.
Les informations sont traités toutes les 0.7s comme le fait le programme d'origine fournit avec.


> Attention : Le contrôle toutes les 0.7s peux ralentir votre Jeedom.
> Personnellement utilisé, pas de problème particulier de charge avec un RPI2.

## Configuration
La configuration est très simple et ne nécéssite pas d'installation suplémentaire.

### Equipement

![GitHub Logo](/../images/zm_config.JPG)

Il faut renseigner (ici avec des valeurs par défaut) :
- IP : 192.168.1.166
- Port : 1234
- PortWeb : 80
- Login : admin
- Password : 12345678
- Rafraichissement : 700
- Version : 1

### Commandes

![GitHub Logo](/../images/zm_com.JPG)

Il est possible d'ajouter des commandes de type info et action.
Le bouton "Ajout auto" permet de générer automatiquement pour les 8 relais :

- Off : Permet de désactiver le relai.
- On : Permet d'activer le relai.
- Temporisation : Permet d'activier le relai pendant le temps paramétré sur la carte.
- Etat : Permet de connaitre l'état du relai.

Et les 8 entrées :
- Etat : Permet de connaitre l'état de l'entrée.


