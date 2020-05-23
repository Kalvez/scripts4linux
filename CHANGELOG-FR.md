### ..::CHANGELOG - MAI  23 2020::..
```
-Infos: Correction de bug.
-Backup: Une option 'restaurer' a été ajoutée. Vous avez maintenant le choix de soit sauvegarder, soit restaurer.
```
### ..::CHANGELOG - MAI  09 2020::..
```
-Le support du dossier '/etc/' est abandonné dans le script 'backup'.
```
### ..::CHANGELOG - MAI  08 2020::..
```
-Concernant 'archive' et 'backup' : Moins d'arguments ont été utilisés avec 'pv' parce qu'ils n'étaient pas si pertinents car ils n'affichaient pas d'informations correctes (comme le taux de compression et la taille du fichier compressé).
-Réparation de bugs mineurs.
```
### ..::CHANGELOG - MAI  07 2020::..
```
-Les scripts 'backup' et 'archive' n'utilisent plus le format '*.zip' au profit du format d'archivage '*.tar'.
-Utilisation de 'pigz' pour une optimisation du temps de compression de l'archive.
```
### ..::CHANGELOG - MAI  06 2020::..
```
-Le script "auto-installer" a été mis à jour pour des raisons de compatibilité avec Pop!_OS 20.04.
-Une ligne 'Graphiques' a été ajoutée au script 'infos' qui permet désormais d'afficher le processeur graphique de l'ordinateur.
-Création du changelog Anglais.
```
### ..::CHANGELOG - AVR. 09 2020::..
```
-Le script 'disks' a été modifié. Maintenant il dispose d'un affichage standard ne nécessitant pas les droits super-utilisateur et d'un affichage avancé les nécessitants.
```
### ..::CHANGELOG - JAN. 06 2020::..
```
-DeepinOS fait désormais partie des distributions supportées.
```
### ..::CHANGELOG - NOV. 03 2019::..
```
-Raspbian est fait désormais partie des distributions officiellement supportées.
-Les scripts et les paquets nécessaires à l'installation de Mozilla Firefox Quantum ont été supprimés car ils n'étaient plus mis à jour depuis un petit moment. Il est désormais impossible d'installer Quantum via ce pack de scripts.
```
### ..::CHANGELOG - OCT. 22 2019::..
```
-Tous les scripts se sont vus dotés d'une refonte graphique. Surtout 'infos'.
-Le script 'unlocker' supporte maintenant l'accès aux disques chiffrés en lecture/écriture.
-Toujours plus de couleur.
```
### ..::CHANGELOG - OCT. 08 2019::..
```
-Grâce au paquet 'pv', les scripts 'archive' et 'backup' disposent maintenant d'une barre de progression plus "user-friendly" qu'une cascade de texte.
```
### ..::CHANGELOG - OCT. 07 2019::..
```
-ZorinOS fait maintenant partie des distributions supportées par le script.
-Ajout du script 'update-git' qui permet de mettre à jour automatiquement le dépôt de 'scripts4linux'.
```
### ..::CHANGELOG - OCT. 04 2019::..
```
-Ajout de la résolution d'écran sur le script "infos" dans les informations matérielles.
```
### ..::CHANGELOG - SEP. 30 2019::..
```
-Corrections mineures.
```
### ..::CHANGELOG - SEP. 06 2019::..
```
-Manjaro/Mandriva sont maintenant supportées, dans la limite du possible : dislocker n'est pas dans les dépôts officiels donc ne sera pas présent dans le pack tant que je n'aurai pas trouvé comment l'intégrer.
-Le script 'upgrade' n'est pas nécessaire compte-tenu que la commande de MàJ de pacman effectute un 'update', 'upgrade' et 'dist-upgrade'.
```
### ..::CHANGELOG - SEP. 05 2019::..
```
-La version Anglaise des scripts est enfin arrivée.
-L'installateur à changé et est maintenant global. C'est "auto-installer".
-L'organisation des dossiers à complètement changé.
-Les distributions basées sur Debian/Ubunu ont maintenant leurs dossiers, en fonction de la distribution sur laquelle on se trouve.
-Il n'y plus de soucis avec Linux Mint.
-La version et la date du BIOS dans "infos" ont été fusionnées.
-Pas mal d'erreurs ont été corrigées.
```
### ..::CHANGELOG - AOU. 31 2019::..
```
-Le script "infos" passe à sa version 3.0 et devient encore plus complet qu'avant. Les données sont en plus grand nombre et sont organisées de manière plus lisible.
```

### ..::CHANGELOG - AOU. 27 2019::..
```
-Le script "version" est devenu "infos", il affiche désormais plus d'informations de manière mieux ordonnée.
-Le script "install-scripts" a été mis à jour pour migrer le script "version" vers "infos".
-La commande "apt clean" est revenue au sein des scripts "update" et "upgrade". L'approbation pour "apt autoremove" est désormais automatique sur ces deux scripts.
```
### ..::CHANGELOG - AOU. 22 2019::..
```
-Les lignes servant à nettoyer les paquets non-utilisés dans les scripts 'update' et 'upgrade' ont été changées de "apt clean" à "apt autoremove".
```
### ..::CHANGELOG - JUI. 10 2019::..
```
-Le script 'unlocker' a été ajouté à la suite de scripts déjà disponibles. Celui-ci permet de garantir un accès en lecture seule à un lecteur verrouillé via Bitlocker.
-Le script 'backup' a été mis à jour pour maintenant aussi sauvegarder le dossier '/etc/'.
-Le script 'install-script' a été mis à jour en conséquence de l'arrivée de 'unlocker' parmi la suite de scripts déjà disponible.
```
### ..::CHANGELOG - MAR. 27 2019::..
```
-Des erreurs ont été corrigées quant au datage des changelogs de "Scripts4Linux".
-La mise en page est désormais de mise dans le changelog.
```
### ..::CHANGELOG - FEV. 15 2019::..
```
-Mise à jour mineure et amélioration du script "restore-firefox-esr".
-Ajout sur 'get-firefox' d'un script vérifiant qu'il est bien exécuté sur Debian.
-Ajout sur 'install-scripts' d'un script vérifiant qu'il est bien exécuté sur Debian au moment de l'installation des scripts nécessaires à l'installation de Firefox Quantum. Ajout de commandes pour ajouter la permission d'exécution de chaque script avant l'installation de ceux-ci dans '/usr/bin'.
```
### ..::CHANGELOG - FEV. 14 2019::..
```
-Le script d'installation des autres scripts a été mis à jour. Maintenant il est possible d'installer automatiquement les scripts avec leurs dépendances, un disclaimer a donc été rajouté avant l'installation des paquets nécéssaires au bon fonctionnement des scripts.
-Le script "get-firefox" a été mis à jour. Un disclaimer apparaît maintenant avant l'installation de Firefox Quantum.
-"arcive" est toujours une beta, mais il est désormais possible d'archiver plus de trois éléments.
-Ajout d'un  "README" en bonne et due forme.
-Joyeuse Saint-Valentin.
```
### ..::CHANGELOG - MAR. 22 2018::..
```
-Le script d'installation des autres scripts à été mis à jour.
-Maintenant quand Firefox est installé ou mis à jour à travers les scripts 'get-firefox' et 'update-firefox', le nom du raccourcis dans GNOME passe de "Firefox ESR" à "Firefox Quantum".
-Quand Firefox Quantum est désinstallé à travers 'restore-firefox-esr', le nom de "Firefox Quantum" est changé en "Firefox ESR".
```
### ..::CHANGELOG - MAR. 9 2018::..
```
-Pour faciliter l'installation des scripts, 'install-script' a été créé. Pour le lancer, vous allez avoir besoin des privilèges superutilisateur. Sans ça, vous ne pourriez pas l'utiliser.
-Le script 'update' a aussi été mis à jour (lol). La commande de mise à jour pour mettre à jour Firefox Quantum a été supprimée du script. Vous aurez besoin de lancer 'update-firefox' pour le mettre à jour.
-Le scritp 'archive' a été ajouté à la liste des scripts. Vous pouvez utiliser ce script pour archiver des données, et ça va les sauvegarder dans un fichier '.zip' nommé comme ceci : archive_nomChoisi_année-mois-jour.zip
-Et basiquement quelques MàJ et des corrections mineures.
```
### ..::CHANGELOG - MAR. 7 2018::..
```
-Premier envoi de mes scripts sur GitHub.
-Quelques scripts auront besoin de permissions pour être exécutés comme des exécutables. Pour ça, lancez un 'chmod +x'.
-C'est tout pour le moment, bonne journée.
```
