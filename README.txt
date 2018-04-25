
1) Créez un projet console C# et ajoutez le sur github (5 points)
 ->creer un depot git sur github

 ->shift+ clique droit pour ouvrir powershell

 ->git init pour initialiser git sur le dossier du partiel

 ->ajouter a mon fichier .git la liaison entre github et le dossier avec cette ligne "  git remote add origin https://github.com/quadeur06/BASQUINPARTIELAVRIL.git"

 -> creer un fichier .gitignore dans le meme dossier et ajouter .vs/ pour eviter une erreur

 -> ajouter tout les fichiers avec git add --all

 -> faire un commit avec git commit -m " premier commit"

 -> envoyer avec git push -u origin master

 3 )Ajouter une branche « dev » (2 points)

-> ajout d'une branche avec  git checkout -b "dev"

 4) Puis dans cette branche ajoutez un hello world dans votre application console (3 points)

-> creation d'un hello world dans le program.cs avec console.writeline("hello world");

-> ) git add --all pour ajouter tout les fichiers

-> ) git commit -m "envoie vers dev" pour faire un commit

-> ) git push -u origin dev pour envoyer dans la branche dev

 5 )Intégrez la branche dans votre branche principale (5 points)

-> allez vers  la branche master en faisant : git checkout master

 ->  faire git merge dev  pour ajouter les modifications de la branche dev à la branche master

  6 )Supprimez maintenant votre répertoire avec votre projet et récupérer le projet depuis github
(pensez à mettre à jour votre README avec la commande utilisée)

 -> ) pour telecharger le dossier a partir de github faire " git clone https://github.com/quadeur06/BASQUINPARTIELAVRIL.git"

 -> ) et voila fini :D ( le readme.txt à jour se trouve dans la branche master)
