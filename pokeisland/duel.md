---
icon: boxing-glove
---

# Duel

<div align="center">
  <img src="https://commons.wikimedia.org/wiki/Special:FilePath/Battle_icon_%28crossed_swords%29.svg" alt="Icône duel" width="72">
</div>

## Duel 1v1 : face à face (avec une mise)
Le **Duel** te permet de défier un autre joueur et de te mesurer à lui en Pokémon. Oui, il y a une mise : si tu gagnes, tu repars avec de quoi remplir ton sac et ton portefeuille.

## Envoyer un défi
Utilise :
`/duel <pseudo> [mise]`

Exemples :
- `/duel Alex`
- `/duel Alex 2500`

## Répondre au défi
Quand quelqu’un te défie, tu peux répondre avec :
- `/duel accept` (tu relances le duel)
- `/duel deny` (tu refuses)

## Mettre un blocage (éviter les défis)
Si tu ne veux plus que quelqu’un te défie :
- `/duel block <pseudo>`
- `/duel unblock <pseudo>`

## Règles pratiques (pour que ça marche)
À surveiller :
- Le duel doit se faire à une **distance maximale de 20 blocs** (sinon la demande est refusée).
- Il y a une **mise maximale** : `30000`.
- Il y a un **délai de demande** côté serveur (config : `request-timeout`).

## Conditions fréquentes
Le serveur peut refuser le duel si par exemple :
- tu n’as pas assez de **Pokécoins** pour la mise,
- l’adversaire n’a pas assez de **Pokémon** pour participer,
- la demande est trop “loin” (distance) ou arrive au mauvais moment (délai).

## Résultat
Le serveur affiche des messages quand :
- ton défi est accepté/refusé,
- tu remportes ou perds le duel (et donc la somme associée).
