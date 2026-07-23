# Suivi santé v15 — version GitHub

## Durée par créneaux horaires
- Les douleurs et les autres symptômes disposent de 24 boutons, de 00 h à 23 h.
- Plusieurs créneaux peuvent être sélectionnés.
- Raccourcis : heure de saisie, toute la journée et effacer.
- Au moins un créneau est nécessaire pour enregistrer une douleur ou un autre symptôme.

## Graphiques
- En regroupement horaire, une saisie est répartie dans chacun de ses créneaux.
- En regroupement quotidien ou mensuel, l’intensité est pondérée par le nombre de créneaux.
- Exemple : une intensité de 8 sur cinq créneaux contribue comme cinq valeurs de 8.
- Le graphique de quantité affiche le nombre de créneaux concernés.

## Compatibilité
- Le champ `hourSlots` est facultatif.
- Les anciens exports restent importables.
- Une ancienne saisie sans `hourSlots` est rattachée à l’heure de sa saisie.
- Le calcul du score QDSA reste inchangé.
