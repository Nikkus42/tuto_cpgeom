**Tuto création Git**
----

**Préalable**, création d'un répo distant sur la plateforme Git

1. Création d'un dossier sur le PC ==> pourle moment, un dossier classique.
2.  On crée le premier fichier readme.md (qui va êtres la page d'accueil de notre repo)
3. On va initialiser ce dossier classique, comme un repo local avec la commande:
```git init```
Cette commande entraine la création d'un sous répertoire **.git**, notre dossier *"classique"* local est devenu un repository au sens git du terme. 
4. On va pousser le Read_me.md dans le *Stage* avec la commande: ```git add```
5. Une fois le fichier remonter dans le stage, on va le remonter dans le commit. Chaque commi, on lui donne un nom. La commande est : ```git commit -m "premier commit"``` (message entre "" apparait dans le Github)
6. Il faut renommer la branche principale. Par défaut, elle se nomme *Master* et Github veut qu'elle s'appelle *Main*. Pour renommer la branche principale, il faut lancer la commande: ``git branch -M main``.
7. On crée le lien entre notre repository locale avec le distant: ``git remote add origin https://github.com/Nikkus42/tuto_cpgeom.git``
8. Notre fichier readme.md est au niveau commit, toujours en local. Il faut le pousser sur le distant avec la commande: `` git push -u origin main``