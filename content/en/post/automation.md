+++
title = 'Hugo Framework'
date = 2023-11-14T13:59:57+01:00
draft = false
+++

# Ce que j'ai retenu de Hugo
**Hugo** permet de générer un site statique (c'est à dire sans backend) facilement par le biais de GitHub Pages.  
Il suffit pour cela d'installer Hugo depuis le terminal puis de créer un dossier grâce aux commandes proposées sur la documentation officielle. 
Il est possible de tester cet environnement en local dans un premier temps avec la commande:.  
````hugo server -D````.  
Le ````-D```` sert ici à afficher également les posts en brouillon.  
Ensuite, il est possible de télécharger un thème, ce qui permet de ne pas débuter de zéro pour modifier son site. 
### On peut ensuite personnaliser ce thème de plusieurs manières. 
Dans un premier temps, les thèmes comportent un dossier appelé "Example Site" dans lequel on peut retrouver un fichier de configuration. Ce fichier permet de modifier des parties générales du site. Ces réglages peuvent donc être amené dans le fichier de configuration de notre propre site et modifier à cet endroit.  
Il est aussi possible de "**surcharger**" notre site en rajoutant des fichiers (qui seront nommés de la même manière que ceux du thème). 
Et bien entendu, on peut rajouter des posts de manière automatique depuis le terminal avec la commande.   
````hugo new content posts/[le_nom_du_post.extension]````.
Cette commande permet de créer un post en markdown (.md) ou html (.html).\
Une fois que le site a été modifié comme souhaité, il s'agit maintenant de le mettre en ligne.  
C'est là que git et Github pages interviennent. Après avoir exécuté la commande ````hugo```` pour que les nouveaux fichiers et autres modifications soient bien prises en compte par le framework on peut alors créer un dossier .github à la racine de notre site où l'on insère une config spécifique, le fait de push les fichiers de notre site depuis la branche locale vers la branche "remote" permet d'automatiquement mettre en ligne le site et tous les changements ultérieur.  

Voilà donc ce que j'ai retenu (et sélectionner comme étant le plus intéressant à réecrire). Pour plus d'informations, n'hésitez pas à vous rendre sur la documentation officielle de [Hugo Framework](https://gohugo.io/)