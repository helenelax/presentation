# Présentation
un dépôt pour mettre mes présentation pour GitPitch  
Chaque présentation a sa propre branche  

### Mode d'emploi
* Les pièces jointes se rangent dans Nextcloud/Partages/Présentation/GitPitch_nom_de_la_branche  
* Quand je crée une nouvelle présentation, je peux choisir, au moment de l'enregistrer de l'enregistrer dans une nouvelle branche. Cela ouvre un *Pull request* qu'il faudra que je ferme dans un second temps  
Cela créé automatiquement une copie du readme.md qui est dans la branche *master*, il faut alors l'actualiser  

Le fichier **PITCHME.yaml** permet de personnaliser la présentation. celui qui est sur la branche Master permet :
* d'ajouter en pied de page sur toutes les diapos : H. Laxenaire - 2017 - CC By Sa 4.0
* d'écraser le CSS par défaut pour qu'il prenne en compte PITCHME.css

Le fichier **PITCHME.css** permet de modifier le CSS par défaut. celui qui est sur la branche Mster permet de :
* supprimer le cadre noir autour des images

* Ajout d'image
```![Le Rochefort](https://ncloud.zaclys.com/index.php/apps/files_sharing/ajax/publicpreview.php?x=1235&y=329&a=true&file=Affichage_GitPitch_Speaker.png&t=CtsMcCp9jN181LZ&scalingup=0)```

### Adresse de présentation
https://gitpitch.com/$user/$repo/$branch   
Exemple : https://gitpitch.com/helenelax/presentation/stage_RS

### Faire apparaitre au fur et à mesure
Slide fragment
**Si pas de mise en forme**  
```- Java
- JavaScript |
- Kotlin     |
- Go         |
- Scala      |
```  
**Si mise en forme**
voir ici : https://github.com/gitpitch/gitpitch/wiki/Fragment-Slides

### Mode présentateur
* Il faut ajouter *Note:* sur les slides
* Il faut presser sur S pour le lancer
* Autoriser les pop-up
* Modules complémentaires : ils ne semblent pas poser de problème sauf que quand *Cookie utodelete* est désactivé, il ne semble plus y avoir de problème d'affichage en mode speaker (*Acces Expired*)
* Si l'affichage de la diapo courante ou de la prochaine ne s'affiche pas correctement (*Access expired*), fermer la fenêtre et cliquer de nouveau sur S, plusieurs fois s'il le faut mais **Il ne faut pas rafraichir la page du speaker !!**
* Options d'affichage   
![Options d'affichage](https://ncloud.zaclys.com/index.php/apps/files_sharing/ajax/publicpreview.php?x=1235&y=329&a=true&file=Affichage_GitPitch_Speaker.png&t=CtsMcCp9jN181LZ&scalingup=0)  
Faire glisser sur le deuxième écran  
Avoir une autre fenêtre de Firefox pour pouvoir faire de stucs sans que les gens voient

