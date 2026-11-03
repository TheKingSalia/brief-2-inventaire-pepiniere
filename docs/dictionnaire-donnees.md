# Dictionnaire des données

> Un champ par ligne, d'après `SUJET.md` et le fichier de `donnees/`. La première ligne sert de modèle.

| Champ | Signification | Type | Règle de validation | Unité | Exemple |
| --- | --- | --- | --- | --- | --- |
| `id` | Identifiant unique | texte | non vide, absent des données | — | N01 |
| `nomCommun` | Nom commun de l'espèce| texte |non vide, absent des données | — | cacao |
| `groupe` | les deux grands groupes de plantes à graines| tableau de chaînes de caractères | non vide| — | angiosperme |
| `nombrePlants` | Nombre de plants disponibles | Nombre | non vide | — | 30 |
| `dateReleve` | Date du comptage | Date | non vide | — | 2026-10-24 |

**Listes de valeurs autorisées** : 
    id: N + le numéro de la ligne,
    nomCommun: Nom commun de l'espèce,
    groupe: choix fait dans `angiosperme` ou `gymnosperme`,
    nombrePlants: un nombre **entier** positif ou nul,
    dateReleve: format `AAAA-MM-JJ`

**Sources** : SUJET.md , plants.json
