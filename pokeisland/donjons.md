---
description: >-
  Six organisations ont installé leurs bases sur l'île. Seul ou jusqu'à six,
  traverse leurs salles et fais tomber leur chef.
icon: dungeon
---

# Donjons

Les **Donjons de Team** sont des expéditions en groupe dans les bases des grandes organisations Pokémon. Tu traverses une suite de **salles** — combats, dresseurs, énigmes — puis tu affrontes le **boss** de la team.

Chaque donjon est **bâti pour ta run** : salles tirées au sort, adversaires et modificateurs différents à chaque fois.

***

## Les six teams

| Donjon | Boss | Tiers |
| --- | --- | :---: |
| 🌊 **Team Aqua** | Archie | 1 à 5 |
| 🌋 **Team Magma** | Max | 1 à 5 |
| 🛸 **Team Galactic** | Hélio | 2 à 5 |
| ⚔ **Team Plasma** | Ghetsis | 2 à 5 |
| 🔥 **Team Flare** | Lysandre | 3 à 5 |
| 🅡 **Team Rocket** | Giovanni | 3 à 5 |

***

## Entrer dans un donjon

1. Trouve un **portail de donjon** dans le monde : une colonne de particules le signale de loin.
2. Fais **clic droit** dessus.
3. Un menu affiche le donjon, son **tier**, les PV des ennemis et les récompenses. Clique pour entrer.

{% hint style="info" %}
Chaque portail a **son tier** (1 à 5) et mène toujours **à la même team**. Pour changer de difficulté, trouve un autre portail.
{% endhint %}

Aucune clef ni ticket n'est nécessaire : les donjons de team sont en **accès libre**.

***

## Jouer en groupe

Jusqu'à **6 joueurs** par run. Forme ton groupe **avant** d'entrer : c'est le **chef** qui fait entrer tout le monde en cliquant sur le portail.

| Commande | Effet |
| --- | --- |
| `/donjon groupe invite <joueur>` | Invite un joueur (il a 60 s pour répondre) |
| `/donjon groupe accept` | Accepte une invitation |
| `/donjon groupe deny` | La refuse |
| `/donjon groupe list` | Qui est dans ton groupe |
| `/donjon groupe leave` | Quitte le groupe |
| `/donjon groupe kick <joueur>` | Retire un joueur (chef seulement) |
| `/donjon groupe disband` | Dissout le groupe (chef seulement) |

{% hint style="warning" %}
Personne ne peut **rejoindre une run déjà commencée**. Tout le groupe entre ensemble.
{% endhint %}

***

## Les tiers

| Tier | Salles (boss compris) | Niveau des Pokémon |
| :---: | :---: | :---: |
| **1** | 3 | ~45 |
| **2** | 3 à 4 | |
| **3** | 4 | |
| **4** | 4 à 5 | |
| **5** | 5 à 6 | ~78 |

Plus le tier monte, plus les ennemis sont résistants, plus les **élites** sont fréquents… et plus les récompenses sont grosses.

***

## Les salles

| Salle | Objectif |
| --- | --- |
| 🐾 **Mobs** | Élimine tous les Pokémon de la salle |
| 🌊 **Vagues** | Survis à 2 vagues d'ennemis |
| 🏟️ **Arène** | 3 duels d'affilée au centre, de plus en plus forts |
| 🧑 **Dresseur** | Bats les sbires de la team |
| 🎖️ **Dresseur d'élite** | Des sbires mieux équipés |
| 👑 **Champion** | Un dresseur avec une équipe complète de 6 |
| 💀 **Mini-boss** | Un Pokémon bien plus résistant que les autres |
| 🧩 **Énigme** | Active les leviers de la salle |
| 🔥 **Boss** | Le chef de la team. Sa vie est **partagée** entre tous les joueurs |

Certaines salles portent un **modificateur**, affiché dans leur nom :

* **FUREUR** — des ennemis qui frappent très fort ;
* **CARAPACE** — des ennemis très résistants ;
* **ÉLITE** — des ennemis de plus haut niveau ;
* **HARGNE** — des ennemis de soutien.

Une fois l'objectif rempli, avance jusqu'au **cercle lumineux** au sol, après les deux statues : il t'envoie dans la salle suivante.

***

## Mourir n'est pas la fin

* Si tu tombes, tu restes **à terre 30 secondes**. Un coéquipier peut te **relever** en restant **5 secondes** à moins de 3 blocs de toi.
* Au bout de **3 morts**, tu es éliminé de la run.
* Si tu te déconnectes, ta place est gardée **2 minutes**.

***

## Ce qui est bloqué pendant une run

* `/spawn`, `/home`, `/tp`, `/tpa`, `/warp`, `/rtp`, `/back` et toute téléportation hors de la salle. Pour sortir : `/donjon leave`.
* Rien ne tombe au sol dans une salle, et on ne ramasse pas ce qui vient de l'extérieur.
* **30 secondes** entre deux pommes dorées, **90 secondes** pour une pomme dorée enchantée.
* Une run dure **1 heure maximum**.

***

## Récompenses

Chaque salle terminée rapporte des **PokéDollars** et des **Points Donjon** à **chaque membre** du groupe. Terminer la run ajoute une prime en PokéDollars et un **bonus de Points Donjon**.

| Tier | Bonus de fin | Total approximatif par joueur |
| :---: | :---: | :---: |
| **1** | 1 à 2 | ~6 Points Donjon |
| **2** | 2 à 4 | ~12 |
| **3** | 4 à 7 | ~18 |
| **4** | 7 à 12 | ~32 |
| **5** | 12 à 20 | ~55 |

Le boss rapporte à lui seul **5 Points Donjon** (avant le multiplicateur du tier).

{% hint style="success" %}
Si tu n'es pas connecté au moment du versement, tes récompenses t'attendent : elles te sont livrées à ta prochaine connexion (`/donjon rewards` pour les récupérer tout de suite).
{% endhint %}

***

## La Boutique Donjon

Les Points Donjon se dépensent dans la **Boutique Donjon** : `/donjon shop`. **94 articles sur 6 pages**, tu choisis ce que tu veux.

| Page | Contenu | Prix |
| --- | --- | :---: |
| **Soins** | Potions, Guérison, Rappels, Huile, Max Élixir, PP Plus | 2 à 25 |
| **Poké Balls** | Rapide, Chrono, Sombre, Filet, Scuba, Bis, Luxe, Balls Noigrume, Rêve Ball, Ultra Ball | 3 à 120 |
| | **Master Ball** | 1 200 |
| **Entraînement** | Bonbons Exp. XS à XL, Super Bonbon, Multi Exp, Œuf Chance, Nœud Destin | 3 à 150 |
| | Objets Pouvoir (Poids, Poignée, Ceinture, Lentille, Bandeau, Chaîne) | 400 |
| **Évolution** | Les 10 pierres d'évolution, Pierre Ovale | 25 |
| | Câble Link | 60 |
| **Objets tenus** | Restes, Ceinture Force, Casque Brut, Grosses Bottes, Évoluroc, Ceinture Pro, Cape Furtive, Dé Pipé, Herbe Miroir… (29 objets) | 60 à 300 |
| **Raretés** | 🥚 **Œuf Shiny** | 2 000 |
| | 🌌 **Œuf Céleste** | 3 000 |

{% hint style="info" %}
La Boutique Donjon ne vend **pas** ce que propose déjà la [Boutique Combat](tour-de-combat.md#la-boutique-combat) (menthes, vitamines, objets Choix, Orbe Vie, cristaux Z…) : les deux se complètent.
{% endhint %}

***

## Commandes

| Commande | Effet |
| --- | --- |
| `/donjon groupe …` | Gérer ton groupe (voir plus haut) |
| `/donjon leave` | Quitter la run en cours |
| `/donjon status` | État de ta run |
| `/donjon shop` | La Boutique Donjon |
| `/donjon rewards` | Récupérer tes récompenses en attente |
| `/donjon stats` | Tes statistiques |
| `/donjon top` | Classement |
