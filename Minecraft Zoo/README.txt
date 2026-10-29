MINECRAFT ZOO 

Fichiers inclus :
- minecraft-zoo.html : version corrigée du jeu.
- electron/ : squelette de projet pour créer une application Windows avec Electron.
- android/ : squelette de projet Android WebView.

Corrections de cette version :
- sauvegardes locales dans 5 emplacements ;
- export du zoo en fichier JSON et import d’un fichier partagé ;
- 5 skins du joueur, appliqués aux différentes parties du modèle et mémorisés ;

À savoir :
- le partage transmet une copie du zoo par fichier JSON ; ce n’est pas du multijoueur en direct.
- les projets Electron/Android sont des bases de compilation, pas des exécutables/APK déjà compilés.
- Three.js est chargé depuis un CDN, donc le jeu nécessite une connexion Internet au lancement.
- Le JavaScript a passé une vérification syntaxique Node.js ; un test complet dans le navigateur reste nécessaire.
