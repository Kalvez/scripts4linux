### ..::CHANGELOG - SEP. 05 2019
```
-La version Anglaise des scripts est enfin arrivée.
-L'installateur à changé et est maintenant global. C'est "auto-installer".
-L'organisation des dossiers à complètement changé.
-Les distributions basées sur Debian/Ubunu ont maintenant leurs dossiers, en fonction de la distribution sur laquelle on se trouve.
-Il n'y plus de soucis avec Linux Mint.
-La version et la date du BIOS dans "infos" ont été fusionnées.
-Pas mal d'erreurs ont été corrigées.
```
### ..::CHANGELOG - AOU. 31 2019
```
-Le script "infos' passe à sa version 3.0 et devient encore plus complet qu'avant. Les données sont en plus grand nombre et sont organisées de manière plus lisible. 
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
### ..::CHANGELOG - JUL. 10 2019::..
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
### ..::CHANGELOG - FEB. 15 2019::..
```
-Mise à jour mineure et amélioration du script "restore-firefox-esr".
-Ajout sur 'get-firefox' d'un script vérifiant qu'il est bien exécuté sur Debian.
-Ajout sur 'install-scripts' d'un script vérifiant qu'il est bien exécuté sur Debian au moment de l'installation des scripts nécessaires à l'installation de Firefox Quantum. Ajout de commandes pour ajouter la permission d'exécution de chaque script avant l'installation de ceux-ci dans '/usr/bin'.
```
### ..::CHANGELOG - FEB. 14 2019::..
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
