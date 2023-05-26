Quand je prend un nouveau projet et un page de ce projet je dois identifier tous les éléments visuels dont j'aurai besoin et commencer par établir des simmilitudes pour ne pas me épéter dans mon code 

Faisons un exemple
les repertoires clones ne sont pas des branches 
mais dosier tout court
La commande git remote add crée un enregistrement de connexion avec un dépôt distant. Après avoir ajouté un dépôt distant, vous pourrez utiliser son nom comme raccourci pratique dans d’autres commandes Git1. Par exemple, vous pouvez utiliser git fetch <nom> pour créer et mettre à jour des branches de suivi à distance <nom>/<branche>2.
Je retiens aussi que quand on crée une nouvelle branche on l'a crée a partir de l'ancienne , cela veut dire que les fichiers de l'ancienne branche seront contenue dans la nouvelle mais avec les modifications effectué dessus 
Quand on fait un pushage de  cette nouvelle branche github nous propose de faire un pull request . C'est quoi le pull request j'ai dit plus haut que lorsqu'on crait une nouvelle branche elle trouvait son origine de la branche principale et que tous les fichiers de la branche principale de se retrouvait dans la branche nouvellement crée . On peut alors operer des modifications sur les fichgiers de la nouvelle branche crée . 
Dès qu'on fait les commits et le pushage des element github vas nous proposer de faire un pull resquet c'est à dire de lier la nouvelle branche à l'ancienne en gros former l'abre quoi pour la nouvelle fonctionnalité . 
github notifie les modifications et fait la fusion . ainsi on as une nouvelle branche 
mais on peut choisir de fusioner cette branche avec le main pour ca il faut faire le merge et dans les entreprises les collaborateurs doivent d'abord reviews votre travail. 

git status permet de voir ce qui commité ou pas 
git commit -a -m " " vas en plus de commiter vas faire le stage préalable de tous les fichiers traqués 
 