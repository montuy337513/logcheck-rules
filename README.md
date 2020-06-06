# logcheck-rules

Règles de filtrage personnelles pour rendre les rapports **logcheck** plus pertinents.
Les filtres finissent par -local pour ne pas se faire effacer lors d'une mise à jour possible de **logcheck**.

## À savoir

J'utilise ces règles sur des serveurs équipés d'une distribution Debian.
Elles sont testées sur :
* Debian 8 - Jessie
* Debian 9 - Stretch
* Debian 10 - Buster
Ces règles doivent fonctionner sur d'autre distributions Linux.

## Installation

Copiez les fichiers présents dans ignore.d.server sur votre système Debian (dans /etc/logcheck/ignore.d.server)

