## Les branches de repo Git

Il est de bonne pratique de ne pas travailler sur la branche principale qui est dédiée à la procduction

- Créer une nouvelle branche *dev* et basculer dessus:

        git checkout -b dev

- la commande ``git banch`` permet de savoir sur quelle branche on se situe:

        
        git branch
        * dev
         main
             
- Pour pousser cette nouvelle branche, le premier push se fait:

        git push -u origin dev

- Ensuite il y a qu'un push simple à faire:

        git commit -a -m "modif qui fait add + commit"

        git push

    ==> branche bien à faire
