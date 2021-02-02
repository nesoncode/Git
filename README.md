# Git test cours n°2

Bouloulouloulou

## Configuration de git en local 

Dans le terminal, avec la composante git config, on va pouvoir configurer certaines informations afin de signer correctement les commits 

On a ajouté le nom d'utilisateur : git config --global user.name "nom_user"

On a ajouté l'adresse email : git config --global user.email "adresse@email"

On a vérifié grâce à : git config --global --list 

## git clone

Cette commande permet de récupérer une copie d'un dêpot distant sur notre machine.
On peut ainsi travailler en local avec VSCode, ce qui est plus pratique que de le travailler directement sur github


## git pull

Avec cette commande, on va pouvoir récupérer le projet distant mis à jour dans notre dépot local

## git add

Dans VSCode, on peut ajouter une nouvelle version d'un fichier à la zone de surveillance en cliquant sur le bouton + dans la section "Controle de code source"

##  git commit 

Avec cette commande, on enregistre dans l'historique une nouvelle version de notre application. Dans VSCode, dans la section "Controle de code source", on a une zone de saisie pour indiquer le message du commit (message le plus précis possible afin de retrouver facilement les différentes cersions du projet.)

## git push

Afin de garder aussi ressemblant que possible le dépot local et le dépot distant, on va envoyer les modifications sur github avec la commande push