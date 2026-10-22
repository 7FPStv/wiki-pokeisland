---
description: >-
  L'Appel des Abysses : pêche des Pokémon et 48 poissons de collection, monte
  ton métier jusqu'au niveau 50, fais évoluer ta canne et réveille le Léviathan.
icon: fish
---

# Pêche

La **pêche** est un métier à part entière. Chaque prise te rapporte de l'**XP de pêche**, parfois un **trésor**, et surtout un **poisson de collection** à faire inscrire dans ton carnet. Tout se gère depuis `/peche`.

{% hint style="info" %}
Ta progression (niveau, carnet, Écailles) est **commune à tous les serveurs** : tu la retrouves partout.
{% endhint %}

***

## Comment pêcher

1. Lance une **Poké Canne** (celle de Cobblemon ou une [canne de pêche PokeIsland](#les-cannes)) dans l'eau.
2. Quand ça mord, un **mini-jeu** s'ouvre : réussis **3 étapes en 15 secondes**.
3. Réussi : le Pokémon remonte comme d'habitude, et tu reçois en plus ton poisson de collection directement dans ton inventaire.

### Le mini-jeu

| Variante | Ce qu'il faut faire |
| ------------------------ | ------------------------------------------------------- |
| **Ferrage précis** | Clique quand le curseur entre dans la zone encadrée. |
| **Anneau de remous** | Clique quand l'anneau mobile rejoint l'anneau cible. |
| **Poisson en mouvement** | Clique quand l'hameçon est aligné sur le poisson. |
| **Réflexe gauche/droite** | Clique du **côté demandé** (clic gauche ou clic droit). |

Contrôles : clic gauche/droit, Espace, Entrée ou les flèches.

{% hint style="warning" %}
Un clic raté, **Échap** ou les 15 secondes écoulées font **fuir la prise** : pas de poisson, pas d'XP.
{% endhint %}

### Zones de pêche

Les **zones de pêche** se reconnaissent à leur **eau teintée en bleu**. C'est là que la pêche rapporte le plus. `/peche zones` liste les lieux et le niveau requis.

Tu peux aussi pêcher **hors zone**, mais à taux réduits :

| | En zone | Hors zone |
| --------------------- | :-----: | :-------: |
| Poisson de collection | 100 % | 35 % |
| XP de pêche | ×1 | ×0,5 |
| Chances de trésor | ×1 | ×0,35 |

***

## Les 48 poissons de collection

Huit poissons par rareté, de la Sardine argentée au Poisson des souhaits. La rareté est tirée à chaque prise :

| Rareté | Poissons | Chance par prise |
| ------------- | :------: | ----------------------: |
| Commun | 8 | 78 % |
| Peu commun | 8 | 18 % |
| Rare | 8 | 3,5 % |
| Épique | 8 | 0,45 % |
| **Légendaire** | 8 | 0,049 % (≈ 1 sur 2 000) |
| **Mythique** | 8 | 0,049 % (≈ 1 sur 2 000) |

{% hint style="info" %}
Ces chances sont **de base**. Ta canne, ton appât et les zones bonus les augmentent (voir plus bas).
{% endhint %}

### Poissons mystères

Environ **15 %** des poissons arrivent sous forme de **poisson mystère**. L'Archiviste doit l'**analyser** pour révéler l'espèce — elle est décidée dès la pêche, l'analyse ne relance rien.

***

## L'Archiviste et le carnet

Le carnet ne se remplit **pas tout seul** : il faut apporter tes prises à l'**Archiviste** (le PNJ de la pêche, aussi accessible depuis `/peche`).

* **Nouvelle espèce** → **Déposer au carnet** : le poisson est consommé et inscrit.
* **Espèce déjà inscrite** → **Vendre contre des Écailles**.
* **Poisson mystère** → **Analyser** d'abord, puis déposer ou vendre.

### Prix de vente

| Rareté | Écailles |
| ---------- | -------: |
| Commun | 10 |
| Peu commun | 25 |
| Rare | 75 |
| Épique | 250 |
| Légendaire | 1 000 |
| Mythique | 5 000 |

{% hint style="success" %}
**Carnet complet** : inscrire les 48 poissons te rapporte un **Chiyu de pêche**, une seule fois par joueur.
{% endhint %}

{% hint style="info" %}
Inventaire plein ? Tes prises t'attendent dans `/mailbox`.
{% endhint %}

***

## Les Écailles et la boutique

Les **Écailles** sont la monnaie de la pêche, séparée de l'argent du serveur. Tu les gagnes en vendant tes doublons, en tournoi et en montant de niveau.

La **boutique** de l'Archiviste vend les **améliorations de canne** — c'est **le seul moyen** de les obtenir (hors trésors très rares) :

| Amélioration | Prix | Niveau requis |
| --------------------- | ----: | :-----------: |
| Hameçon renforcé | 150 | 1 |
| Ligne tressée | 400 | 8 |
| Moulinet des marées | 900 | 15 |
| Moulinet d'argent | 1 800 | 22 |
| Noyau de tempête | 3 500 | 28 |
| Cœur d'étoile | 7 000 | 40 |

***

## Les cannes

Toutes les cannes partent de la **Poké Canne de Cobblemon**. Chaque canne se fabrique avec **la canne précédente au centre** et **deux améliorations** de son palier de part et d'autre, plus des matériaux.

| Canne | Fabriquée depuis | Amélioration | Niveau | XP | Meilleurs poissons | Trésors | Shiny |
| ------------------------- | --------------------- | ------------------- | :----: | :---: | :----------------: | :-----: | :----: |
| Canne vive | Poké Canne | Hameçon renforcé | 1 | ×1,25 | ×1,0 | ×1,0 | +2 % |
| Canne exploratrice | Canne vive | Hameçon renforcé | 5 | ×1,0 | ×1,2 | ×1,0 | +3 % |
| Canne corallienne | Canne vive | Ligne tressée | 8 | ×1,5 | ×1,1 | ×1,0 | +3 % |
| Canne aux trésors | Canne vive | Ligne tressée | 10 | ×1,0 | ×1,0 | ×2,0 | +4 % |
| Canne des marées | Canne exploratrice | Moulinet des marées | 15 | ×1,2 | ×1,4 | ×1,2 | +4 % |
| Canne abyssale | Canne exploratrice | Moulinet des marées | 20 | ×1,1 | ×1,1 | ×1,5 | +5 % |
| Canne du savant | Canne corallienne | Moulinet d'argent | 22 | ×2,0 | ×1,0 | ×1,2 | +5 % |
| Canne du grand large | Canne des marées | Moulinet d'argent | 25 | ×1,1 | ×1,7 | ×1,0 | +6 % |
| Canne des tempêtes | Canne aux trésors | Noyau de tempête | 28 | ×1,2 | ×1,2 | ×3,0 | +7 % |
| Canne lunaire | Canne abyssale | Noyau de tempête | 32 | ×1,6 | ×1,3 | ×2,0 | +8 % |
| Canne astrale | Canne du savant | Cœur d'étoile | 40 | ×2,3 | ×1,3 | ×2,5 | +10 % |
| **Canne du Léviathan** | Canne des tempêtes | Cœur d'étoile | 45 | ×2,0 | ×1,8 | ×3,5 | +12 % |

* **Niveau** : niveau de pêche requis pour utiliser la canne.
* **Meilleurs poissons** : multiplie les chances des poissons Rare et au-dessus.
* **Shiny** : bonus de chance shiny sur les Pokémon pêchés.

{% hint style="info" %}
Les recettes exactes (matériaux autour de la canne) sont visibles dans ton livre de recettes en jeu.
{% endhint %}

### Les appâts

Ils s'accrochent à la canne comme ceux de Cobblemon.

| Appât | Recette (sans forme) | Effet |
| ------------------------ | --------------------- | --------------------------------------------------------- |
| Appât des marées (×4) | Blé + Algue | Réduit l'attente avant la touche |
| **Appât raffiné** (×4) | Blé + Carotte dorée | Favorise les Pokémon rares **et** les meilleurs poissons (×1,5) |
| Appât des profondeurs (×4) | Blé + Poche d'encre | Favorise les Pokémon aquatiques des profondeurs |

***

## Niveaux et récompenses

Chaque prise réussie donne **20 XP** (avant bonus). Le métier monte jusqu'au **niveau 50**, et chaque niveau demande un peu plus d'XP que le précédent. `/peche` affiche ton niveau.

**À chaque niveau** : 2 Bonbons Exp. M et **20 Écailles × ton niveau**. En plus, des paliers :

| Niveau | Récompense |
| :----: | --------------------------------------- |
| 5 | 3 Super Bonbons, 1 CT Aléatoire |
| 10 | Cristal IV Parfait, +500 Écailles |
| 15 | 10 Appâts raffinés |
| 20 | Mega Gemme Aléatoire |
| 25 | Œuf Shiny Aléatoire |
| 30 | 2 Cristaux IV Parfaits, +1 000 Écailles |
| 35 | Œuf Céleste Aléatoire |
| 40 | Master Ball |
| 45 | Œuf Légendaire |
| **50** | **Chiyu de pêche SHINY** |

### Contrat du jour

Chaque jour, un contrat demande **15 prises**. Valide-le avec `/peche contrats valider` pour gagner **150 XP** et une **perle marine**. Il se renouvelle à minuit (heure de Paris).

***

## Trésors

À chaque prise, tu peux aussi remonter un trésor (chances de base, multipliées par ta canne et les zones bonus) :

* **Fragment des abysses** (3 %) et **Perle marine** (0,5 %) : matériaux des cannes.
* **Autres trésors** (2,5 %) : Bonbons Exp., Super Bonbons, CT Aléatoires, Tickets Safari, cristaux d'EV et d'IV, améliorations de canne, Mega Gemmes, Œufs Shiny / Céleste / Légendaire… et, très rarement, une **Master Ball**.

***

## Zones bonus, bancs et tournois

### Zones bonus

Une zone de pêche est **renforcée** à tour de rôle, et le bonus **change de zone toutes les heures**. Son eau prend une **couleur dorée**. Bonus de base : **XP ×1,5**, **meilleurs poissons ×2**, **trésors ×1,5**. `/peche bonus` montre la zone active et le temps restant.

### Bancs de poissons

Toutes les 15 minutes, un **banc** apparaît dans une zone (remous visibles, coordonnées annoncées). Pendant **5 minutes**, l'XP est **doublée** dans un rayon de 8 blocs autour.

### Tournois

Un tournoi classe les pêcheurs pendant un temps limité, selon un mode :

* **Poids** : la plus grosse prise ;
* **Quantité** : le plus de prises ;
* **Diversité** : le plus d'espèces différentes.

Il faut au moins **3 prises** pour être classé. Le podium reçoit des Écailles : **1 500 / 800 / 400**. `/peche tournoi` affiche le classement en direct, `/peche tournoi dernier` les résultats précédents.

***

## Le Léviathan des Abysses

Pendant une **collecte**, pêcher dans une zone peut te rapporter des **lots d'écailles de Léviator**. Offre-les à un **autel du Léviathan** : tous les serveurs remplissent le **même autel**. Une fois l'objectif atteint, le **Léviathan** est invoqué.

C'est un **boss en temps réel** (comme les [Boss](evenements/boss.md)) : tu le frappes et tu esquives ses attaques — Marée abyssale, Geysers, Hydrocanon. Il ne se capture pas.

{% hint style="warning" %}
Les écailles d'autel sont des **objets d'événement**, à ne pas confondre avec les Écailles de la boutique. Un lot reste lié à sa collecte.
{% endhint %}

`/peche communaute` affiche la progression.

***

## Commandes

| Commande | Description |
| -------------------------------- | ------------------------------------------ |
| `/peche` | Menu principal : profil, niveau, records |
| `/peche aide` | Guide « Comment jouer ? » en six étapes |
| `/peche carnet [page] [rareté]` | Ton carnet des 48 poissons |
| `/peche sac` | Tes prises présentes dans l'inventaire |
| `/peche pnj` | Menu de l'Archiviste |
| `/peche pokemon [page]` | Historique des Pokémon pêchés |
| `/peche contrats [valider]` | Contrat du jour |
| `/peche zones` | Lieux de pêche et niveaux requis |
| `/peche bonus` | Zone bonus active et temps restant |
| `/peche tournoi [dernier]` | Tournoi en cours ou précédent |
| `/peche top` | Records de poids du réseau |
| `/peche communaute` | Progression vers le Léviathan |

{% hint style="info" %}
**Conseils**

* Pêche **en zone**, et de préférence dans la **zone bonus** du moment.
* Garde tes doublons : vendus à l'Archiviste, ils financent tes améliorations de canne.
* Pour chasser les légendaires et mythiques, vise une canne à fort bonus **meilleurs poissons** (Canne des marées, du grand large, du Léviathan) avec un **Appât raffiné**.
{% endhint %}
