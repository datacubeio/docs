# Restauration d'une sauvegarde

## Récupération du fichier
Vous devez commencer par télécharger votre sauvegarde directement via votre panel

## Suppresion du chiffrement de la sauvegarde
Une fois que vous avez récupérer le fichier, vous devez déchiffrer celui-ci, pour cela, voici la commande :
openssl aes-256 -d -a -in VOTRE_SAUVEGARDE.tar.gz -out VOTRE_SAUVEGARDE_decrypt.tar.gz

## Désarchivage de l'archive
Vous pouvez maintenant désarchiver votre sauvegarde et restaurer vos donnée.
