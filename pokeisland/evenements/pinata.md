---
description: >-
  Un Pokémon géant apparaît, tout le serveur lui tape dessus, et chaque coup
  fait tomber des bonbons. Littéralement.
icon: candy-cane
---

# Piñata

Tous les jours à **18h** (heure de Paris), une **Piñata Pokémon** apparaît en jeu : un Pokémon géant, entouré d'un halo arc-en-ciel, qui se balade dans la zone. Tout le monde peut le frapper, et **chaque coup peut faire tomber une récompense**. `/pinata`

{% hint style="info" %}
La vie de la Piñata est **commune à tout le réseau**. Le classement aussi. Peu importe le serveur sur lequel tu joues : tu tapes sur la même Piñata que tout le monde.
{% endhint %}

***

## Comment ça marche

* Une Piñata apparaît en **plusieurs exemplaires en même temps** (6 à 15 selon le Pokémon), éparpillés autour du point d'apparition. L'événement se termine quand la **dernière** tombe.
* Tu la frappes **au corps à corps**. Les projectiles et les attaques de Pokémon ne comptent pas.
* Il faut être à **5 blocs maximum**, et il y a un délai de **0,4 seconde** entre deux coups.
* Chaque coup enlève **1 point de vie**, quelle que soit ton arme : tout le monde participe à égalité, pas besoin d'un stuff de folie.
* La Piñata **se déplace** : suis-la si tu veux continuer à taper.

Une **boss bar**, un **hologramme** au-dessus d'elle et une **actionbar** t'affichent en permanence les coups restants.

***

## Quelle Piñata ce soir ?

Chaque jour à 18h, **une seule Piñata** est tirée au sort parmi les huit :

| Piñata | Chance d'être tirée | Exemplaires | PV chacune | Joueurs requis |
| ---------------- | :-----------------: | :---------: | :--------: | :------------: |
| **Pikachu** | 33,8 % | 10 | 600 | 10 |
| **Évoli** | 20,3 % | 6 | 1 000 | 5 |
| **Ronflex** | 13,5 % | 10 | 600 | 5 |
| **Ectoplasma** | 10,1 % | 6 | 1 000 | 5 |
| **Dracolosse** | 8,1 % | 8 | 750 | 6 |
| **Dracaufeu** | 5,4 % | 8 | 750 | 8 |
| **Léviator** | 5,4 % | 8 | 750 | 7 |
| **Mewtwo** | 3,4 % | 15 | 400 | 20 |

Quel que soit le Pokémon, l'événement totalise **6 000 PV**, soit 6 000 coups à donner à plusieurs.

{% hint style="warning" %}
Une Piñata est **annulée** s'il n'y a pas assez de joueurs connectés sur le réseau au moment prévu. Elle est alors retentée un peu plus tard : 20 minutes en général, 30 minutes pour Pikachu, 45 minutes pour Mewtwo.
{% endhint %}

Des annonces préviennent **10 minutes**, **5 minutes** et **1 minute** avant l'apparition. <kbd>**/pinata next**</kbd> t'indique la prochaine.

***

## Durée

Une Piñata reste **20 minutes** maximum. Si elle n'est pas détruite d'ici là, elle disparaît. Des alertes tombent avant la fin.

***

## Récompenses

### À chaque coup

**Un coup sur deux** en moyenne fait tomber **un objet** (jet indépendant à chaque coup). Le butin est le même pour toutes les Piñatas :

| Objet | Part des gains |
| ----- | :------------: |
| **Bonbons Exp.** XS · S · M · L | 46 % (16,6 · 13,8 · 10,1 · 5,5) |
| **Bonbons qui baissent un EV** (6 sortes) | 22 % (3,7 chacun) |
| **Bonbons d'EV** — Santé, Force, Armure, Esprit, Mental, Sprint | 19 % (3,2 chacun) |
| **Super Bonbons** ×1 à 3 | 6 % |
| **Bonbon Exp. XL** | 2,3 % |
| **Super Bonbon** | 2,3 % |
| **Pierre Foudre** | 1,4 % — 2 max par joueur et par Piñata |
| **Balle Lumière** | 0,5 % — 1 max par joueur, 10 par Piñata |

### Bonus

* **Dernier coup** : celui qui détruit une Piñata gagne **5 000 PokéCoins**.
* **Participation** : à partir de **10 coups** donnés, tu reçois **500 PokéCoins**.
* Un **classement des coups** est tenu à l'échelle du réseau : `/pinata top`.

{% hint style="success" %}
Inventaire plein ? Rien n'est perdu : la récompense est mise de côté et tu la récupères avec <kbd>**/pinata rewards**</kbd>.
{% endhint %}

Les quotas (Pierre Foudre, Balle Lumière) sont comptés à l'échelle du réseau : impossible de les contourner en changeant de serveur.

***

## Commandes

| Commande | Effet |
| ------------------- | ------------------------------------- |
| `/pinata` | Informations sur la Piñata en cours |
| `/pinata next` | Prochaine apparition prévue |
| `/pinata top` | Classement des coups (top 10) |
| `/pinata teleport` | Te rapproche de la Piñata |
| `/pinata rewards` | Récupère tes récompenses en attente |
