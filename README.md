# Today — distribution

Ce dépôt public ne sert qu'à distribuer l'application **Today** :

- `appcast.xml` — le flux que l'app interroge pour détecter les mises à jour ;
- les *releases* — les `.dmg` téléchargeables, signés avec une clé EdDSA.

Le code source est privé. Tout ici est généré par `Scripts/release.sh`.

## Installation

Télécharge le `.dmg` de la [dernière release](../../releases/latest), ouvre-le
et glisse **Today** dans Applications. Les mises à jour suivantes s'installent
depuis l'app : *Réglages → Général → Rechercher une mise à jour*.
