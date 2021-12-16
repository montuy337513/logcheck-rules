# logcheck-rules

Règles de filtrage personnelles pour rendre les rapports **logcheck** plus pertinents.
Les filtres finissent par -local pour ne pas se faire effacer lors d'une mise à jour possible de **logcheck**.

## À savoir

J'utilise ces règles sur des serveurs équipés d'une distribution Debian.
Elles sont testées sur :
* Debian 8 - Jessie
* Debian 9 - Stretch
* Debian 10 - Buster
* Debian 11 - Bullseye

Ces règles doivent fonctionner sur d'autre distributions Linux.

## Installation

Copiez les fichiers présents dans ignore.d.server sur votre système Debian (dans /etc/logcheck/ignore.d.server)
La prise en charge se fait automatiquement.

## Note

Les fichiers *-local contiennent des règles fonctionnannt sur tous les serveurs

Les fichiers *-perso sont des fichiers contenant des règles spécifiques, il faut les adapter à votre configuration.  

* dovecot-perso : modifier/dupliquer les lignes suivantes en spécifiant vos adresses mails

## Problemes

si vous rencontrez un problème avec ses règles,vous pouvez me contacter directement ici. 