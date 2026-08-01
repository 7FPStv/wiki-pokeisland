---
description: >-
  Deviens champion d'arène, ou capture une arène et fais-la rapporter. Ici, ce
  sont les joueurs qui tiennent les gyms.
icon: shield-halved
---

# Arènes joueurs

À côté des [arènes du PokéWorld](pokeworld/arenes.md) tenues par des PNJ, PokeIsland a deux systèmes d'arènes gérées **par les joueurs eux-mêmes**.

***

## Les arènes de champions

Certaines arènes sont confiées à un **joueur champion**, choisi par le staff. C'est lui qui décide quand son arène est ouverte, et c'est lui que les autres viennent défier. `/arene`

### Les arènes disponibles

| Arène | Type |
| ---------------- | -------- |
| Arène Feu | Feu |
| Arène Eau | Eau |
| Arène Plante | Plante |
| Arène Dragon | Dragon |

Le menu `/arene` t'indique en un coup d'œil lesquelles sont **ouvertes** (pastille verte) et lesquelles sont **fermées** (pastille rouge).

### Côté challenger

1. Ouvre `/arene` et repère une arène ouverte.
2. Va défier son champion.
3. En cas de victoire, tu reçois la récompense de l'arène — **une seule fois par arène**.

Exemple pour l'**Arène Feu** : 5 000 PokéCoins, 200 XP Dresseur, de la Poudre Flamme, des Boules de Feu, et une annonce à tout le serveur.

{% hint style="success" %}
**Battre les quatre arènes** débloque un bonus de complétion : **50 000 PokéCoins**, 1 000 XP Dresseur, une Étoile du Nether, le grade **Maître d'arène**, et une annonce à tout le serveur.
{% endhint %}

### Côté champion

Si tu es champion d'une arène, tu peux :

* **ouvrir et fermer** ton arène quand tu veux,
* définir le **point d'apparition** des challengers,
* **valider** une victoire de challenger.

{% hint style="info" %}
Les arènes de champions sont **synchronisées entre les serveurs** : ton statut de champion et l'état de ton arène te suivent partout.
{% endhint %}

***

## Les arènes capturables

Le second système est un système de **territoires**. Tu captures une arène, tu la défends, et elle te rapporte tant que tu la tiens.

| Règle | Valeur |
| ------------------------------- | ------ |
| Arènes possédées simultanément | **3** maximum |
| Défenseurs par arène | **6** Pokémon |
| Arènes qui rapportent en même temps | **3** |
| Temps limite d'un combat de capture | 15 min |

### Défendre

Quand tu captures une arène, tu y laisses une **équipe de défense** (jusqu'à 6 Pokémon). Les autres joueurs qui veulent te la prendre devront battre cette équipe — et ton **skin** apparaît sur le dresseur défenseur.

### Les revenus

Tant que tu tiens une arène, elle te verse des récompenses à intervalle régulier :

| Intervalle | Gain |
| ---------- | ------------------------- |
| 1 minute | 1 diamant + 500 PokéCoins |
| 6 heures | 2 000 PokéCoins |
| 12 heures | 5 000 PokéCoins |
| 24 heures | 12 000 PokéCoins |

{% hint style="warning" %}
Tu dois être **connecté** pour toucher les revenus de tes arènes. Une arène tenue pendant que tu es hors ligne ne rapporte rien.
{% endhint %}

***

## Commandes

| Commande | Effet |
| ----------- | -------------------------------------------- |
| `/arene` | Menu des arènes de champions |
| `/arena` | Menu des arènes capturables |
| `/badges` | Tes badges obtenus |
