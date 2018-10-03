# Changements sur le jeu de données
Les changements de schéma du jeu de données SECMAR sont répertoriés ci-dessous.

### 2018-10-03
- La colonne `operations_stats.numero_semaine` a été renommée en `operations_stats.annee_semaine`. Elle contient l'année et la semaine, par exemple `2018-10`
- La colonne `operation_stats.semaine` a été ajoutée. Elle contient uniquement le numéro de la semaine, par exemple `10`

**Commits**:
- https://github.com/entrepreneur-interet-general/predisauvetage/commit/e85941f836d6a718d1164a36afd119cde8b374e3

### 2018-09-18
- Correction des fuseaux horaires pour les CROSS de Nouvelle-Calédonie et Polynésie
- La colonne `operations.numero_sitrep` est désormais renseignée pour les opérations avant 2010
- Ajout des colonnes `operations_stats.nombre_personnes_blessees` et `operations_stats.nombre_personnes_blessees_sans_clandestins` dénombrant le nombre de personnes blessées dans chaque opération
- Ajout de la colonne `operations.vent_direction_categorie` indiquant la direction du vent (par exemple : `nord-ouest`)

**Commits**:
- https://github.com/entrepreneur-interet-general/predisauvetage/commit/ee04005d8778bcbf2e1566ad5b6010980e5b0dfd
- https://github.com/entrepreneur-interet-general/predisauvetage/commit/9a3a271188a0001e69b18f617e862e1f5ff91465
- https://github.com/entrepreneur-interet-general/predisauvetage/commit/3d4d21a244c36979cee300ee70782e4982e9c919
- https://github.com/entrepreneur-interet-general/predisauvetage/commit/a158bbcc2ca8da0f9c043de3938667216264045d

### 2018-08-23
Les fichiers CSV sont désormés triés dans l'ordre croissant selon la valeur de la colonne `operation_id`.

**Commit**:
https://github.com/entrepreneur-interet-general/predisauvetage/commit/699d48987f95fc05892f8fdd8d63e42320d677d9

### 2018-08-08
Table `operations_stats`:
- ajout de la colonne `est_dans_stm`
- ajout de la colonne `nom_stm`
- ajout de la colonne `est_dans_dst`
- ajout de la colonne `nom_dst`

**Commit**:
https://github.com/entrepreneur-interet-general/predisauvetage/commit/765dfdbebedbac642a0eacd6017312b2803fa5db

### 2018-07-22
Table `operations_stats`:
- ajout de la colonne `distance_cote_metres`
- ajout de la colonne `distance_cote_milles_nautiques`

**Pull request**:
https://github.com/entrepreneur-interet-general/predisauvetage/pull/42

### 2018-07-10
Table `operations_stats`:
- ajout de la colonne `date`
- ajout de la colonne `jour_semaine`

**Pull request**:
https://github.com/entrepreneur-interet-general/predisauvetage/pull/40

### 2018-07-09
Table `operations_stats`:
- ajout de la colonne `est_jour_ferie`
- ajout de la colonne `est_weekend`
- ajout de la colonne `jour_semaine`
- la colonne `annee` utilise la date de l'alerte en heure locale du CROSS coordinateur et non l'heure UTC
- la colonne `mois` utilise la date de l'alerte en heure locale du CROSS coordinateur et non l'heure UTC
- la colonne `jour` utilise la date de l'alerte en heure locale du CROSS coordinateur et non l'heure UTC

**Pull request**:
https://github.com/entrepreneur-interet-general/predisauvetage/pull/38

### 2018-07-02
Publication initiale
