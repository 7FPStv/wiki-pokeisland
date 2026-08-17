---
description: >-
  Un Pokémon géant apparaît, tout le serveur lui tape dessus, et chaque coup
  fait tomber des bonbons. Littéralement.
icon: candy-cane
---

# Piñata

À certains horaires, une **Piñata Pokémon** apparaît en jeu : un Pokémon géant, entouré d'un halo arc-en-ciel, qui se balade dans la zone. Tout le monde peut le frapper, et **chaque coup peut faire tomber une récompense**. `/pinata`

{% hint style="info" %}
La vie de la Piñata est **commune à tout le réseau**. Le classement aussi. Peu importe le serveur sur lequel tu joues : tu tapes sur la même Piñata que tout le monde.
{% endhint %}

***

## Comment ça marche

* Une Piñata apparaît en **plusieurs exemplaires en même temps** (6 à 15 selon le Pokémon), éparpillés autour du point d'apparition. L'événement se termine quand la **dernière** tombe.
* Tu la frappes **au corps à corps**. Les projectiles et les attaques de Pokémon ne comptent pas.
* Il faut être à **5 blocs maximum**, et il y a un délai de **0,5 seconde** entre deux coups.
* Chaque coup enlève **1 point de vie**, quelle que soit ton arme : tout le monde participe à égalité, pas besoin d'un stuff de folie.
* La Piñata **se déplace** : suis-la si tu veux continuer à taper.

Une **boss bar**, un **hologramme** au-dessus d'elle et une **actionbar** t'affichent en permanence les coups restants.

***

## Les Piñatas et leurs horaires

| Piñata | Exemplaires | PV chacune | Joueurs requis | Horaires (heure de Paris) |
| ---------------- | ----------- | ---------- | -------------- | ---------------------------------------- |
| **Ronflex** | 10 | 90 | 5 | Lun. & mer. 17h, sam. 14h |
| **Évoli** | 6 | 100 | 5 | Mar. & jeu. 19h, dim. 15h et 20h |
| **Ectoplasma** | 6 | 100 | 5 | Mar. 21h, ven. 22h |
| **Dracolosse** | 7 | 110 | 6 | Lun. 19h, ven. 19h et 21h30 |
| **Léviator** | 8 | 120 | 7 | Jeu. 21h, dim. 18h |
| **Dracaufeu** | 8 | 130 | 8 | Mer. 20h, sam. 16h et 21h |
| **Pikachu** | 10 | 100 | 10 | Lun., mer. & ven. 18h — sam. 14h, 18h, 21h |
| **Mewtwo** | 15 | 250 | 20 | Événement spécial |

{% hint style="warning" %}
Une Piñata est **annulée** s'il n'y a pas assez de joueurs connectés sur le réseau au moment prévu. Elle est alors retentée 30 minutes plus tard.
{% endhint %}

Des annonces préviennent **10 minutes**, **5 minutes** et **1 minute** avant l'apparition.

***

## Durée

Une Piñata reste **15 minutes** maximum. Si elle n'est pas détruite d'ici là, elle disparaît. Des alertes tombent à 5 min, 1 min et 10 secondes de la fin.

***

## Récompenses

* **Environ un coup sur deux** donne une récompense — c'est un jet indépendant à chaque fois.
* La récompense peut être : des **PokéCoins**, des objets, des **clés de coffre**, des **Pokémon**, ou de l'expérience.
* Le **dernier coup** (celui qui détruit une Piñata) donne un bonus.
* Un **classement des coups** est tenu à l'échelle du réseau : `/pinata top`.

{% hint style="success" %}
Inventaire plein ? Rien n'est perdu : la récompense est mise de côté et tu la récupères avec <kbd>**/pinata rewards**</kbd>.
{% endhint %}

Certaines récompenses ont des **quotas** (par joueur, par événement, par jour, par semaine). Ces quotas sont comptés à l'échelle du réseau : impossible de les contourner en changeant de serveur.

***

## Commandes

| Commande | Effet |
| ------------------- | ------------------------------------- |
| `/pinata` | Informations sur la Piñata en cours |
| `/pinata next` | Prochaine apparition prévue |
| `/pinata top` | Classement des coups (top 10) |
| `/pinata teleport` | Te rapproche de la Piñata |
| `/pinata rewards` | Récupère tes récompenses en attente |
