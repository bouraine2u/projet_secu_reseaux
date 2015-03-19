# projet_secu_reseaux
Projet Sécurité des réseaux Master2 SSI Metz 2015

Le but du projet est de réaliser une étude passive des réseaux Wifi á portée d'1 appareil mobile sur lequel on embarquerait un OS Unix.
(faire une étude du vide : pas vraiment ca mais plutot l'ensemble du wifi en passif)

Analyse passive de données en se baladant avec un telephone portable
Capturer et analyser ce que l'on peut.

Perspectives :
-faire une cartographie
-Evaluer la sécurité de chaque Access Point

Etapes :
DONE 1- Rooter le téléphone Android
DONE 2- Installer Linux Deploy
DONE 3- Installer Kali Linux sur la carte SD via Linux Deploy
DONE 4- Tester la carte Wifi ( apt-get install wireless-tools 'iwlist wlan0 scanning' nous permet de faire une liste des SSID disponibles)
DONE 5- Ecrire un script qui loggue ce qu'il écoute (un 'iwlist' toutes les 5s devrait faire l'affaire) done par un script bash --> voir script_5s répertorié environ 200 réseaux Wifi
NOK 6- Trouver le moyen de logguer les positions géographiques (4G ?) (test wifite également done)
7- Essayer de retranscrire ces logs sur une map et améliorer les scripts bash par un langage plus poussé
