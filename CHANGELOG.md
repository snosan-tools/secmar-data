# Changelog
Ce fichier répertorie les changements de schéma du jeu de données SECMAR.


## 2018-07-09
Table `operations_stats`:
- ajout de la colonne `est_jour_ferie`
- ajout de la colonne `est_weekend`
- ajout de la colonne `jour_semaine`
- la colonne `annee` utilise la date de l'alerte en heure locale du CROSS coordinateur et non l'heure UTC
- la colonne `mois` utilise la date de l'alerte en heure locale du CROSS coordinateur et non l'heure UTC
- la colonne `jour` utilise la date de l'alerte en heure locale du CROSS coordinateur et non l'heure UTC

#### Pull requests
https://github.com/entrepreneur-interet-general/predisauvetage/pull/38

## 2018-07-02
Publication initiale
