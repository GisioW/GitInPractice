# Commande git

## Créer un nouveau référentiel via ligne de commande
> git init

> git add <liste des fichiers/repertoire à ajouter> (git add . pour ajouter tout)

> git commit -m '[message de commit]'

> git branch -M main

> git remote add origin [url_du_referentiel]/<nom_projet>.git

> git push -u origin main

## Pousser un référentiel existant via la ligne de commande

> git remote add origin [url_du_referentiel]/<nom_projet>.git

> git branch -M main

> git push -u origin main

```
        exemple --message = -m, --all = -a, --list = -l
```
### Explication des commandes Git
>**git init** : Permet la création du référentiel git en local sur votre machine.

>**git add** :  Permet l'ajout de vos modifications dans un index pour permet l'envoi vers le référentiel à distance. Git devrait suivre le contenu d'un fichier à mesure qu'il change. En résumé elle est utilisée à la fois  pour ajouter initialement un fichier au référentiel Git et pour demander que les modifications apportées au fichier soient utilisées lors du prochain commit.

>**git status** : 

>**git log**:L'historique de Git est la liste complète de tous les commits effectués depuis la création du référentiel.

