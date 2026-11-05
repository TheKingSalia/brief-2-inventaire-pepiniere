# Relevé des tests

> Écrivez le résultat attendu avant d'essayer. Un écart n'est pas une faute : notez-le, corrigez, refaites le test.

**Calculs à la main** : 
    stock total: 240,
    nombre de plants et d'espèces de chaque groupe: 
        angiosperme: 8 espèces et 222 plants
        gymnosperme: 2 espèces et 18 plants
    lignes à moins de 10 plants:
        N09 = 8 plants et N10 = 10 plants

**Essais dans le menu** : un ajout valide (encore là après redémarrage), chaque règle refusée, une recherche introuvable, chaque tri, la synthèse, un choix inconnu.

| Action | Attendu | Obtenu | Testeur |
| --- | --- | --- | --- |
| Ajouter un plant saisi | Le plant est parfaitement rajouté et s'affiche dans le fichier des données| Succès | Salia KAMAGATE |
| Ajouter un plant non parfaitement saisi | Le plant n'arrive pas a etre rajouté et l'utilisateur reçoit des messages d'erreur là où les informations sont incorrectement saisies | succès | Salia KAMAGATE |
| Lister l'inventaire des plants | Tous les plants présents dans les données s'affichent correctement | Succès | Salia KAMAGATE |
| Faire des recherches sur les plants | Pouvoir retrouver un ou plusieurs plants en fonction du nom, code ou groupe botannique | Succès | Salia KAMAGATE |
| Pouvoir trier les groupes botaniques | Les plants d'un certain groupe botanique sont classés dans l'ordre croissant | Succès | Salia KAMAGATE |
| Choix inconnu | Lorsque l'utilisateur rentre un choix inconnu, le menu lui est renvoyé précédé de choix inconnu | Succès | Salia KAMAGATE |

**Sur un autre poste** (`git clone`, `node app.js`, `npm test`, en suivant le README) : 
    Testeur: KONE PAGADJOUFOU; SERIFOU CHEICK; TOURE TIOH LAGNIME EMMANUEL