# Changelog
Ce fichier répertorie les changements de schéma du jeu de données SECMAR.

## 2018-08-08
Table `operations_stats`:
- ajout de la colonne `est_dans_stm`
- ajout de la colonne `nom_stm`
- ajout de la colonne `est_dans_dst`
- ajout de la colonne `nom_dst`

#### Commit
https://github.com/entrepreneur-interet-general/predisauvetage/commit/765dfdbebedbac642a0eacd6017312b2803fa5db

## 2018-07-22
Table `operations_stats`:
- ajout de la colonne `distance_cote_metres`
- ajout de la colonne `distance_cote_milles_nautiques`

#### Pull requests
https://github.com/entrepreneur-interet-general/predisauvetage/pull/42

## 2018-07-10
Table `operations_stats`:
- ajout de la colonne `date`
- ajout de la colonne `jour_semaine`

#### Pull requests
https://github.com/entrepreneur-interet-general/predisauvetage/pull/40

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
