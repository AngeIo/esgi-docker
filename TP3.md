# Docker - TP3 : Utilisation des conteneurs de manière autonome
> **Objectifs du TP** :
>- Autonomie sur l'utilisation des conteneurs
>

## 1- La mise en pratique autonome

> Que permet de faire la commande suivante `docker container run alpine ls -l` ?
Elle permet de lancer un conteneur avec l'image alpine pour exécuter la commande "ls -l", affiche le résultat et il s'arrête juste après

> Quel argument permet de supprimer un container automatiquement une fois celui-ci arrêté ?
docker container prune

> Comment partager un volume entre mon hôte local et un conteneur ? 
-v cheminsurlhotesource:cheminsurleconteneurdestination

> Que permet de faire la commande docker suivante `docker container exec <nom_conteneur> ls -l` ?
Elle permet, sur un conteneur déjà lancé ... d'exécuter la commande "ls -l", affiche le résultat

> Quelle ligne de commande docker permet de créer un conteneur de type serveur web permettant d'héberger votre code situé dans votre répertoire courant ?
