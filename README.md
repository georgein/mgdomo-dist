# MG Domo - plugins pour Jeedom

**MG Domo** est un ensemble de plugins pour [Jeedom](https://www.jeedom.com), conçus pour fonctionner ensemble à partir
d'un socle commun, le plugin **MG Domo**. Ce dépôt sert uniquement à leur distribution.

## Documentation

**https://georgein.github.io/mgdomo-dist/** : présentation de l'écosystème, installation, table des matières et aide de
chaque plugin (PDF consultables directement dans le navigateur).

- [MG_Domo.pdf](https://georgein.github.io/mgdomo-dist/MG_Domo.pdf) : présentation générale, installation, liste des plugins
- [mgDomo_APK.pdf](https://georgein.github.io/mgdomo-dist/mgDomo_APK.pdf) : application Android du socle

## Installation

Dans Jeedom (Réglages > Système > Administration > Administration Système), ou en SSH :

```
curl -fsSL https://github.com/georgein/mgdomo-dist/releases/download/master/install_new_station_mgDomo.sh | sudo bash
```

Puis Plugins > Gestion des plugins > MG Domo > Activer. Les autres plugins s'installent et se mettent à jour depuis
MG Domo, onglet **Plugins**, avec contrôle d'intégrité.

## Contenu de la publication `master`

- une archive par plugin (`<plugin>-<version>.tgz`) ;
- `versions.json` : version, date et empreinte md5 de chaque archive, lu par MG Domo ;
- `install_new_station_mgDomo.sh` : installation du socle sur une nouvelle box.

## Aide

Forum Jeedom, ou onglet **Demande d'intervention** de la page MG Domo (diagnostic anonymisé, accès temporaire).
Licence : GNU Affero GPL (AGPL).
