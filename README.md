# SMART STADIUM Project

Code source associé a la version bêta du projet SMART Stadium proposé au concours Vinci STARTUP TOUR 2015/2016

# Projet root smartstadium 

Projet Maven de type pom

# Sous-module backoffice-app

Développé avec Spring boot et angular JS, englobant les webservices partagé avec les applications utilisateurs et 
frontoffice (mobile app) les application backoffice (gestionnaire des évenements d'un stade). 


# Module externe findpath-lib

Pour le moteur de calcul nous avons décidé de le coder en C++ pour des raisons de vitesse et de performance. La dépence 
est utilisé par backoffice app pour exécuter le programme find-path. 

# Module externe mobile-app

Développement avec Ionic

Prérequis : 
Avoir installé : 
npm install -g bower
npm install -g cordova
npm install -g ionic

Application hybride qui sera utilisé par les bornes NFC ainsi que les applications mobiles.

Dépendences cordova à ajouter: 
cordova plugin add phonegap-nfc (https://www.npmjs.com/package/phonegap-nfc)

