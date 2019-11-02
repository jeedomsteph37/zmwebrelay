# ZmWebRelay 


Ce plugin permet de controler les cartes 8 relais "ZmWebRelay" que l'on trouve facilement sur Internet.
Ces cartes possèdent également 8 entrées numériques.
Il est possible de gérer plusieurs cartes en même temps.
A chaque carte est associée un démon qui intéroge la carte toutes les 0.7 secondes (réglabe).

> Remarques : Sur certains équiments, le démon peut consommer de la ressource

## Configuration
La configuration est très simple et nécéssite pas d'installation suplémentaire.
Pour éviter des problèmes d'accès à la carte, les commandes sont envoyées par web et les informationssont récupérées par telnet.

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


