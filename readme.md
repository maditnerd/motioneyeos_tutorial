Caméra de surveillance avec motioneyeOS
-----------

# Installation
Pour installer motioneyeOS, 
* Télécharger l'image 
* Copier le fichier sur une carte micro sd à l'aide de **etcher**
* Mettez la carte SD dans votre Raspberry Pi
* Brancher la caméra à votre Raspberry Pi
* Connectez votre Raspberry Pi à votre box

Image : https://github.com/ccrisan/motioneyeos/releases  
Etcher : https://etcher.io/#downloads

![etcher](https://github.com/maditnerd/motioneyeos_tutorial/raw/master/etcher.png)

# Première connexion
La configuration de motioneyeOS se fait depuis un navigateur web (**chrome**/**firefox** par ex).     
Pour cela il faut connaître l'adresse IP de notre Raspberry Pi.    

Le plus simple est d'utiliser **fing** depuis un **smartphone**   
Apple Store : https://itunes.apple.com/gb/app/fing-network-scanner/id430921107?mt=8    
Google Play : https://play.google.com/store/apps/details?id=com.overlook.android.fing&hl=en_GB    

![fing](https://github.com/maditnerd/motioneyeos_tutorial/raw/master/fing.jpg)

* Tapez l'adresse IP, dans votre barre de recherche.   
![ip](https://github.com/maditnerd/motioneyeos_tutorial/raw/master/ip.png)

* Entrez l'identifiant par défaut
Username: admin
Password: (vide)  

![login](https://github.com/maditnerd/motioneyeos_tutorial/raw/master/password.jpg)

# Configuration
MotionEyeOS va automatiquement detecter votre caméra et l'afficher.

![motioneyeos](https://github.com/maditnerd/motioneyeos_tutorial/raw/master/firstconnection.jpg)

* Cliquer sur les trois barres (en haut à gauche) pour afficher la configuration

## Mot de passe / Paramètres avancés
Tout d'abord nous allons mettre un mot de passe, dans **General Settings**   
Il y a deux utilisateurs **admin** et **user**    
Le premier permet de configurer la caméra et le deuxième simplement de la visionner    

* Entrez un mot de passe 
* Activer **Advanced Settings**, sans ça vous n'aurez pas accès à la majorité de la configuration!

![password](https://github.com/maditnerd/motioneyeos_tutorial/raw/master/generalsettings.jpg)

## Fuseau Horaire  / Nom
* Afin que l'heure soit correcte sur notre caméra, il nous faut régler le fuseau horaire (timeZone)   
* Donner un nom à votre caméra (hostname), vous pourrez ainsi accéder à votre caméra avec son nom au lieu de son IP
* Appliquer les changements en appuyant sur APPLY (bouton en orange)
* Cliquez sur YES pour redémarrer.    
![timezone](https://github.com/maditnerd/motioneyeos_tutorial/raw/master/timezone-hostname.png)

Vous pouvez maintenant vous connecter à votre caméra avec son nom au lieu de l'ip  
![hostname](https://github.com/maditnerd/motioneyeos_tutorial/blob/master/hostname.jpg)

