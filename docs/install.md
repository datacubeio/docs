# Installation de l'agent

Datacube propose une solution pour réaliser vos sauvegarde très rapidement et simplement sans vous prendre la tête avec de lourde configuration.

## Introduction
Datacube n'a pas accès directement a votre serveur, l'agent que nous vous demandons d'installer permet de réaliser puis d'envoyer les sauvegardes via un FTP. Ainsi nous pouvons prendre votre sauvegardes et l'archiver.

L'ensemble des accès que nous vous fournissions doivent être enregistrer de votre côté, et ne doivent pas être partager avec d'autre personne.

## Prérequis
Vous devez avoir crée un serveur sur votre interface et avoir identifier vos identifiants FTP ainsi que votre uid de serveur.

## Installation
Pour installer votre serveur vous devez exéctuer la commande suivante:

wget --no-check-certificate -N https://raw.githubusercontent.com/flemzord/datacube/master/install.sh && bash install.sh

## En vidéo

[![asciicast](https://asciinema.org/a/6k71xck2wu0xmznv7kvc9tmbx.png)](https://asciinema.org/a/6k71xck2wu0xmznv7kvc9tmbx)
