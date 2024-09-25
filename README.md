ok cool
modif branch-a
modif branch b


Exercice GIT base manip 

1/ créer un dossier de projet 

2/ créer 3 dossiers (html/css/js)
mkdir html, css, js

3/ créer les fichiers index.html, index.js et styles.css dans leurs dossiers respectifs
Touch index.html, index.js, style.css

4/ mettre a jour l'ensemble dans le dossier remote
git remote add origin https://github.com/Numazer/go.git

5/ créer une branche "dev"
Git branch dev

6/ lister les branches
Git branch

7/ se positionner sur la branche dev
Git checkout dev

8/ modifier le fichier css 

9/ mettre la modif a jour sur la branche dev
Git commit -m « nommer la modif »

10/ revenir sur la branche master et ouvrir le fichier css (voit-on la modif ?)
Git checkout main

11/ fusionner la branche dev sur la branche master 
Sur la branche main => git merge dev

12/ verifier la modif css
Git diff dev main

13/ retourner sur la branche dev et ajouter un fichier readme.md
Mkdir readme.md sur la branche dev ou dans github ajouter un dossier readme plus git pull sur la branche dev

14/ faire un commit de ce fichier 
Git commit

15/ visualiser les differences avec la commande adéquate
Git diff main dev

16/ créer deux nouvelles branches branch-a et branch-b
git branch branch-a, git branch branch-b

17/  dans chaque fichier readme de chaque branche, ajoutez une ligne spécifique (modif branch-a et branch-b par ex)

18/ comparez les deux branches avec la fonction adéquate 
Git diff branch-a branch-b

19/ mergez la branche a sur master
Sur la branche main => git merge branch-a

20/ mergez la branche b sur master 
Sur la branche main => git merge branch-b

21/ essayez de resoudre le conflit ...
4 possibilités : accepter la modif actuelle.
Accepter la modif entrante
Accetper les deux modifs
Comparer les modifs
+résoudre dans l’éditeur de fusion
