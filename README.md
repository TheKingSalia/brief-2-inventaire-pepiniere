# Inventaire de la pépinière


## Contexte

L'outil est utilisé par le responsable de la pépinière pédagogique. Son besoin est de pouvoir structurer un inventaire et appliquer une classification botanique simple à partir d'une fiche de référence. Il doit pouvoir ajouter un plan ou l'original du relevé. Il veut pouvoir lister l'inventaire(stock total, stock faible…). Cet inventaire est construit en JavaScript avec Node.js

## Prérequis et lancement

- Node.js 20 ou plus récent, Git ; aucune bibliothèque à installer.

```bash
git clone https://github.com/VOTRE-COMPTE/brief-2-inventaire-pepiniere.git
cd brief-2-inventaire-pepiniere
node app.js
npm test
```

Sous PowerShell, si `npm` est bloqué : `npm.cmd test`.

## Fonctionnalités

- [x] Données lues et enregistrées dans `donnees/plants.json`
- [x] Ajouter un plant, saisies invalides refusées sans arrêter le programme
- [x] Lister l'inventaire, message si l'inventaire est vide
- [x] Rechercher par code ou par nom ; filtrer par groupe botanique
- [x] Trier par nombre de plants
- [x] Synthèse : stock total, espèces et plants par groupe, espèce la plus abondante, stocks faibles (≤ 10 plants)
- [ ] Bonus : supprimer et modifier un plant (choix 6 et 7)
- [ ] Bonus : tri décroissant, groupe le plus fourni

## Données

Les données sont fictives et sont fournis par le coach

## Limites

le seuil de 10 plants est un repère de suivi, pas une recommandation de production.
L'application ne tient pas compte des plantes en dehors des angiospermes et des gymnospermes.
L'application ne permet pas encore de supprimer ou de modifier un plant. 
 

## Documents

[Dictionnaire des données](docs/dictionnaire-donnees.md) · [Tâches](docs/taches.md) · [Relevé des tests](docs/releve-tests.md) · [Journal de recherche](docs/journal-recherche.md) · [Fiche agronomique](docs/fiche-agronomique.md) · [Fiche individuelle](docs/fiche-individuelle.md)

## Auteur

Salia Abdallah KAMAGATE, TheKingSalia. Entraide : J'ai aidé pleins de personnes que je pourrais mentionner 
