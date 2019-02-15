..::CHANGELOG - FEB. 15 2018::..

-Mise à jour mineure et amélioration du script "restore-firefox-esr".
-Ajout sur 'get-firefox' d'un script vérifiant qu'il est bien exécuté sur Debian.
-Ajout sur 'install-scripts' d'un script vérifiant qu'il est bien exécuté sur Debian au moment de l'installation des scripts nécessaires à l'installation de Firefox Quantum. Ajout de commandes pour ajouter la permission d'exécution de chaque script avant l'installation de ceux-ci dans '/usr/bin'.

..::CHANGELOG - FEB. 14 2018::..

-Le script d'installation des autres scripts a été mis à jour. Maintenant il est possible d'installer automatiquement les scripts avec leurs dépendances, un disclaimer a donc été rajouté avant l'installation des paquets nécéssaires au bon fonctionnement des scripts.
-Le script "get-firefox" a été mis à jour. Un disclaimer apparaît maintenant avant l'installation de Firefox Quantum.
-"arcive" est toujours une beta, mais il est désormais possible d'archiver plus de trois éléments.
-Ajout d'un  "README" en bonne et due forme.
-Joyeuse Saint-Valentin.

..::CHANGELOG - MAR. 22 2018::..

-Le script d'installation des autres scripts à été mis à jour.
-Maintenant quand Firefox est installé ou mis à jour à travers les scripts 'get-firefox' et 'update-firefox', le nom du raccourcis dans GNOME passe de "Firefox ESR" à "Firefox Quantum".
-Quand Firefox Quantum est désinstallé à travers 'restore-firefox-esr', le nom de "Firefox Quantum" est changé en "Firefox ESR". 

..::CHANGELOG - MAR. 9 2018::..

-Pour faciliter l'installation des scripts, 'install-script' a été créé. Pour le lancer, vous allez avoir besoin des privilèges superutilisateur. Sans ça, vous ne pourriez pas l'utiliser.
-Le script 'update' a aussi été mis à jour (lol). La commande de mise à jour pour mettre à jour Firefox Quantum a été supprimée du script. Vous aurez besoin de lancer 'update-firefox' pour le mettre à jour.
-Le scritp 'archive' a été ajouté à la liste des scripts. Vous pouvez utiliser ce script pour archiver des données, et ça va les sauvegarder dans un fichier '.zip' nommé comme ceci : archive_nomChoisi_année-mois-jour.zip
-Et basiquement quelques MàJ et des corrections mineures.

..::CHANGELOG - MAR. 7 2018::..

-Premier envoi de mes scripts sur GitHub.
-Quelques scripts auront besoin de permissions pour être exécutés comme des exécutables. Pour ça, lancez un 'chmod +x'.
-C'est tout pour le moment, bonne journée.
