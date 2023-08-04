ROG Ally Debloat & Optimization

tout dans ce guide est VOTRE PROPRE RISQUE je ne suis responsable de rien.

Avant tout, vous allez avoir besoin de plusieurs choses :
- une clé USB de minimum 16GB
- un hub USB-C avec 3 entrée USB-A
- clavier
- souris


Tout d'abord, il faut mettre a jour et installer TOUS les drivers disponible via MYASUS/ArmoryCrate/WindowsUpdate.
Je conseille d'installer également tous les drivers presents sur la page des drivers pour la ROG ALLY ci-dessous.

https://rog.asus.com/gaming-handhelds/rog-ally/rog-ally-2023/helpdesk_download/


Il est impératif de faire ça car nous allons Backup tous les drivers pour les modifications suivantes.
Une fois que vous êtes pret, créez un dossier "drivers" dans le disque C: a sa base.
le chemin vers ce dossier sera donc "C:\drivers"

Nous allons maintenant utiliser la commande suivante pour backup tous les drivers.
Lancez le terminal windows avec les droits d'administrateurs et coller cette ligne :


dism /online /export-driver /destination:"C:\drivers"

Maintenant nous allons créer une clé USB Bootable
utilisant la verson allegée de windows 11 "GhostSpectre Superlite SE"

Suivez la procédure fournie par le créateur via ce lien :

https://ghostclouds.xyz/wp/w11-22h2-22621/

Telechargez la version 13, installez egalement Rufus & 7-zip sur leur site respectif.

- https://rufus.ie/fr/#
- https://www.7-zip.org

L'iso de GhostSpectre Superlite SE est compressée au forma .U13
Il faut extraire L'iso via 7-zip et mettez la où vous voulez.
Le mot de passe : 22h2u13







