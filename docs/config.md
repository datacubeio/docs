# Configuration de Datacube

## Information
Maintenant vous devez configurer vos premiers backup, vous avez le choix entre plusieurs profiles "type", il se trouve dans le répertoire /opt/datacube/backup_script.
Vous ne devez pas modifier les scripts directement dans ce dossier, sinon vos modifications seront écrasées lors de la prochaine mise à jour.

## Configuration avancée
Nous avons créé le dossier /opt/datacube/custom_script qui vous permet d'ajouter tous les scripts que vous souhaitez sans qu'il ne soit modifié.
Vous devez ajouter vos scripts custom dans le fichier /opt/datacube/load_script.sh comme dans l'exemple présent dans celui-ci.
Vous pouvez utiliser comme base les scripts de Datacube pour réaliser vos propre script custom.
