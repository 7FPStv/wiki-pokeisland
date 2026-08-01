---
description: >-
  Les cristaux de raid qui poussent dans le monde, et la licence à acheter pour
  débloquer chaque palier de difficulté.
icon: gem
---

# Raid Dens

Des **cristaux de raid** apparaissent naturellement dans le monde. Un clic dessus ouvre un lobby : tu invites des joueurs, et vous affrontez ensemble un **Pokémon de raid** surpuissant. `/dens`

Sur PokeIsland, ces raids sont découpés en **7 tiers de difficulté**, et tu dois **débloquer chaque tier** avant d'y avoir accès.

***

## Trouver un den

* Les cristaux apparaissent dans l'Overworld, environ **1 chunk sur 256**.
* Un den se **réinitialise toutes les 2 heures** : le boss ET le tier changent à chaque cycle.
* Un hologramme au-dessus du cristal t'indique le **tier** du raid — et donc si tu y as droit.

**Répartition des tiers dans la nature :**

| Tier | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| ------ | -- | --- | --- | --- | --- | -- | -- |
| Chance | 9 % | 15 % | 25 % | 25 % | 20 % | 5 % | 1 % |

{% hint style="info" %}
Un raid **raté peut être retenté**. Et les récompenses sont tirées **individuellement** pour chaque joueur : ton voisin peut décrocher un shiny sans que ça t'enlève ta chance.
{% endhint %}

***

## La progression par tier

Tu démarres au **Tier 1**, accessible dès ta première connexion. Pour monter d'un cran, tu dois cumuler **trois choses** :

1. un nombre de **victoires** sur le tier précédent,
2. les **quêtes** du palier,
3. le **paiement de la licence** — toujours la dernière étape.

À partir du **Tier 5**, une **épreuve finale** (ascension) s'ajoute avant le paiement.

| Tier à débloquer | Victoires requises | Sur le tier | Épreuve finale | Prix de la licence |
| ---------------- | ------------------ | ----------- | -------------- | ------------------ |
| **Tier 2** | 5 | Tier 1 | Non | 20 000 |
| **Tier 3** | 10 | Tier 2 | Non | 50 000 |
| **Tier 4** | 15 | Tier 3 | Non | 125 000 |
| **Tier 5** | 20 | Tier 4 | **Oui** | 300 000 |
| **Tier 6** | 25 | Tier 5 | **Oui** | 750 000 |
| **Tier 7** | 35 | Tier 6 | **Oui** | 1 500 000 |

{% hint style="warning" %}
Une victoire n'est comptée que si tu avais **effectivement droit** à ce tier. Inutile d'essayer de te faire inviter dans un raid trop haut : le contrôle se fait aussi à l'entrée du lobby d'un autre joueur, avant la téléportation.
{% endhint %}

Le déblocage des Tiers 4 et plus est **annoncé sur tout le serveur**.

***

## Les quêtes

Chaque palier a ses objectifs, à consulter dans <kbd>**/dens quests**</kbd>. Exemple pour le Tier 2 :

* **Premiers pas** — terminer 3 raids Tier 1
* **Hôte débutant** — héberger et terminer 2 raids Tier 1

Les paliers suivants demandent plus de victoires, plus de raids hébergés, et des objectifs plus variés.

***

## Récompenses des raids

Les récompenses sont distribuées **au hasard** entre les participants. Elles incluent le Pokémon du raid, avec ses IV, sa nature et sa chance d'être shiny.

{% hint style="success" %}
Les IV obtenus en raid affectent les **IV naturels** du Pokémon, pas un entraînement hyper. C'est donc un excellent moyen d'obtenir des Pokémon de qualité compétitive.
{% endhint %}

Au-delà de **4 joueurs** dans un raid, les capacités de soutien partagées sont désactivées : les gros raids se jouent en force brute.

***

## Commandes

| Commande | Effet |
| ------------------- | ------------------------------------ |
| `/dens` | Ouvre le menu de progression |
| `/dens progression` | Ton avancement détaillé |
| `/dens quests` | Les quêtes du palier en cours |
| `/dens tier <1-7>` | Détail d'un tier et ses conditions |
| `/dens stats` | Tes statistiques de raids |
