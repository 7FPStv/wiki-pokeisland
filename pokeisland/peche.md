---
description: >-
  L'Appel des Abysses : pêche des Pokémon et 48 poissons de collection, monte
  ton métier jusqu'au niveau 50, fais évoluer ta canne et réveille le Léviathan.
icon: fish
---

# Pêche

La **pêche** est un métier à part entière. Chaque prise te rapporte de l'**XP de pêche**, parfois un **trésor**, et surtout un **poisson de collection** à faire inscrire dans ton carnet. Tout se gère depuis `/peche`.

{% hint style="info" %}
Ta progression (niveau, carnet, Écailles, contrats) est **commune à tous les serveurs** : tu la retrouves partout.
{% endhint %}

***

## Le principe en bref

La boucle de la pêche tient en cinq étapes :

1. **Tu pêches** avec une Poké Canne et tu réussis le **mini-jeu** à la touche.
2. Le **Pokémon** remonte comme d'habitude (tu peux le combattre et le capturer), **et** tu reçois un **poisson de collection** dans ton inventaire, de l'**XP de pêche**, parfois un **trésor**.
3. Tu apportes tes poissons à l'**Archiviste** : une espèce nouvelle est **déposée au carnet**, un doublon est **vendu contre des Écailles**.
4. Avec tes **Écailles**, tu achètes des **améliorations** pour fabriquer des **cannes** plus puissantes, qui donnent plus d'XP, de meilleurs poissons, plus de trésors et plus de shiny.
5. En montant de **niveau**, tu débloques ces cannes et tu gagnes des **récompenses** à chaque niveau, jusqu'au **Chiyu de pêche shiny** au niveau 50.

À côté, des activités relancent l'intérêt : **contrat du jour**, **zones bonus** qui tournent, **bancs de poissons**, **tournois** et le boss **Léviathan des Abysses**.

***

## Comment pêcher

1. Lance une **Poké Canne** (celle de Cobblemon ou une [canne de pêche PokeIsland](#les-cannes)) dans l'eau.
2. Attends la touche. Quand ça mord, un **mini-jeu** s'ouvre.
3. Réussis **3 étapes en 15 secondes**. À la troisième réussite, la prise remonte toute seule.

Le monde continue de tourner pendant le mini-jeu : évite de pêcher au milieu d'un combat ou à côté d'un monstre.

### Le mini-jeu

Le serveur choisit une variante à chaque touche (jamais deux fois la même d'affilée). Les trois étapes d'une même prise gardent la même variante.

| Variante | Ce qu'il faut faire |
| ------------------------ | ------------------------------------------------------- |
| **Ferrage précis** | Clique quand le curseur entre dans la zone encadrée. |
| **Anneau de remous** | Clique quand l'anneau mobile rejoint l'anneau cible. |
| **Poisson en mouvement** | Clique quand l'hameçon est aligné sur le poisson. |
| **Réflexe gauche/droite** | Clique du **côté demandé** (clic gauche ou clic droit). |

**Contrôles :** clic gauche ou droit, Espace, Entrée ou les flèches. Pour le réflexe, il faut le bon côté : clic gauche ou flèche gauche, clic droit ou flèche droite.

{% hint style="warning" %}
Un clic raté, **Échap**, la perte de la canne, la mort, une déconnexion ou les 15 secondes écoulées font **fuir la prise** : pas de poisson, pas d'XP.
{% endhint %}

{% hint style="info" %}
Le serveur tient compte de ton ping : un léger décalage réseau ne te fait pas rater un clic bien placé.
{% endhint %}

### Zones de pêche

Les **zones de pêche** sont des plans d'eau aménagés par le serveur. Elles se reconnaissent à leur **eau teintée en bleu**, et c'est là que la pêche rapporte le plus. Certaines demandent un **niveau minimum**, d'autres ne s'ouvrent que **de nuit**, **de jour**, **sous la pluie** ou **par beau temps**. `/peche zones` liste les lieux et leur niveau requis.

Tu peux aussi pêcher **n'importe où ailleurs**, mais à taux réduits :

| | En zone | Hors zone |
| --------------------- | :-----: | :-------: |
| Poisson de collection | à chaque prise | 35 % des prises |
| XP de pêche | ×1 | ×0,5 |
| Chances de trésor | ×1 | ×0,35 |

Hors zone, tu gardes toujours les Pokémon et les objets normaux de la pêche Cobblemon.

***

## Les 48 poissons de collection

Il y a **48 poissons**, huit par rareté, de la *Sardine argentée* au *Poisson des souhaits*. À chaque prise, le jeu tire d'abord une **rareté**, puis un poisson au hasard parmi ceux de cette rareté.

| Rareté | Poissons | Chance par prise (de base) |
| ------------- | :------: | -------------------------: |
| Commun | 8 | 78 % |
| Peu commun | 8 | 18 % |
| Rare | 8 | 3,5 % |
| Épique | 8 | 0,45 % |
| **Légendaire** | 8 | 0,049 % (≈ 1 sur 2 000) |
| **Mythique** | 8 | 0,049 % (≈ 1 sur 2 000) |

Un poisson mythique **précis** tombe donc environ **une fois sur 16 000 prises** sans bonus. Chaque prise est un tirage indépendant : il n'y a pas de compteur de « pitié ». Pour améliorer tes chances, voir [Comment se cumulent les bonus](#comment-se-cumulent-les-bonus).

Chaque poisson a aussi un **poids** (en kg), tiré dans la fourchette de son espèce. Ton meilleur poids par espèce est gardé dans le carnet, et le plus lourd du réseau apparaît dans `/peche top`.

Quand quelqu'un inscrit un poisson **légendaire** ou **mythique** au carnet, c'est **annoncé sur tout le réseau**.

### Poissons mystères

Environ **15 %** des poissons arrivent sous forme de **poisson mystère**. Seul l'Archiviste peut l'**analyser** pour révéler l'espèce. L'espèce, la rareté et le poids sont décidés **dès la pêche** : analyser plus tard, changer de serveur ou fermer le menu ne relance rien.

### Un poisson = une prise

Chaque poisson pêché porte un **reçu unique** : il ne s'empile pas avec les autres, et il ne compte **qu'une seule fois** sur tout le réseau.

* Tu peux **échanger ou donner** un poisson : son nouveau propriétaire peut le déposer ou le vendre.
* Un poisson obtenu autrement qu'en pêchant (mode créatif, copie, objet renommé…) **ne vaut rien** chez l'Archiviste.

***

## L'Archiviste et le carnet

Le carnet ne se remplit **pas tout seul** : il faut apporter tes prises à l'**Archiviste**, le PNJ de la pêche. Son menu s'ouvre aussi depuis `/peche`. Il affiche les poissons **réellement présents dans ton inventaire**.

Clique sur un poisson, puis :

* **Nouvelle espèce** → **Déposer au carnet** : le poisson est consommé et l'espèce est inscrite.
* **Espèce déjà inscrite** → **Vendre contre des Écailles** (le prix s'affiche, puis on te demande de confirmer).
* **Poisson mystère** → **Analyser la prise** : le poisson révélé arrive dans ton inventaire, et tu peux ensuite le déposer ou le vendre.

### Prix de vente

Le prix dépend seulement de la rareté, pas du poids.

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
**Inventaire plein ?** Rien n'est jeté par terre : tes poissons et récompenses t'attendent dans `/mailbox`.
{% endhint %}

***

## Les Écailles et la boutique

Les **Écailles** sont la monnaie de la pêche, **séparée de l'argent du serveur**. Ton solde est affiché dans ton profil `/peche` et chez l'Archiviste.

**Comment en gagner :**

* en **vendant** tes doublons à l'Archiviste ;
* en **montant de niveau** (20 × ton niveau à chaque niveau, plus des bonus aux niveaux 10 et 30) ;
* en finissant sur le **podium d'un tournoi**.

**À quoi elles servent :** la **boutique** de l'Archiviste (bouton émeraude dans son menu) vend les **améliorations de canne**. Il n'existe **aucune recette** pour les fabriquer : à part un trésor très rare, la boutique est le seul moyen de les obtenir.

| Amélioration | Palier | Prix | Niveau requis |
| --------------------- | :----: | ----: | :-----------: |
| Hameçon renforcé | 1 | 150 | 1 |
| Ligne tressée | 2 | 400 | 8 |
| Moulinet des marées | 3 | 900 | 15 |
| Moulinet d'argent | 4 | 1 800 | 22 |
| Noyau de tempête | 5 | 3 500 | 28 |
| Cœur d'étoile | 6 | 7 000 | 40 |

Les achats arrivent dans ton inventaire, ou dans `/mailbox` s'il est plein.

***

## Les cannes

Toutes les cannes PokeIsland sont de vraies **Poké Cannes** : elles acceptent les appâts de Cobblemon et les enchantements de pêche.

### Fabriquer une canne

Les cannes forment un **arbre d'évolution** qui part de la **Poké Canne de Cobblemon**. Chaque recette se fait sur l'établi :

* la **canne précédente** au centre ;
* **deux améliorations** de son palier, à gauche et à droite ;
* des **matériaux** autour (perles marines, fragments des abysses, blocs de minerai, Poké Balls…).

La canne précédente est consommée. Le détail des matériaux est visible dans ton **livre de recettes** en jeu.

```
Poké Canne
└─ Canne vive ───────────────┬─ Canne exploratrice ─┬─ Canne des marées ── Canne du grand large
                             │                      └─ Canne abyssale ──── Canne lunaire
                             ├─ Canne corallienne ─── Canne du savant ──── Canne astrale
                             └─ Canne aux trésors ─── Canne des tempêtes ─ Canne du Léviathan
```

### Leurs bonus

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

**Comment lire le tableau :**

* **Niveau** : niveau de pêche requis pour **utiliser** la canne. Tu peux la fabriquer avant, mais pas t'en servir.
* **XP** : multiplie l'XP de pêche de chaque prise.
* **Meilleurs poissons** : multiplie les chances des poissons **Rare, Épique, Légendaire et Mythique**.
* **Trésors** : multiplie les chances de trésor.
* **Shiny** : augmente la chance que le **Pokémon** pêché soit shiny.

Il n'y a pas de canne « meilleure partout » : chaque branche a sa spécialité. La branche **corallienne → savant → astrale** vise l'**XP**, la branche **trésors → tempêtes → Léviathan** les **trésors**, et la branche **exploratrice → marées → grand large** les **meilleurs poissons**.

### Les appâts

Ils s'accrochent à la canne comme ceux de Cobblemon.

| Appât | Recette (sans forme) | Effet |
| ------------------------ | --------------------- | --------------------------------------------------------- |
| Appât des marées (×4) | Blé + Algue | Réduit l'attente avant la touche |
| **Appât raffiné** (×4) | Blé + Carotte dorée | Favorise les Pokémon rares, **et** meilleurs poissons ×1,5 |
| Appât des profondeurs (×4) | Blé + Poche d'encre | Favorise les Pokémon aquatiques des profondeurs |

***

## Comment se cumulent les bonus

Plusieurs sources se **multiplient** entre elles.

| Bonus | Canne | Appât raffiné | Zone bonus | Banc de poissons | Hors zone |
| ------------------ | :---: | :-----------: | :--------: | :--------------: | :-------: |
| XP | ✔ | | ×1,5 | ×2 | ×0,5 |
| Meilleurs poissons | ✔ | ×1,5 | ×2 | | |
| Trésors | ✔ | | ×1,5 | | ×0,35 |

**Exemple :** avec une **Canne du grand large** (×1,7), un **Appât raffiné** (×1,5), dans la **zone bonus** (×2), les poissons Rare et au-dessus sont **×5,1** plus probables qu'à la base. Le bonus « meilleurs poissons » est plafonné à **×10**.

{% hint style="info" %}
« ×5 sur les chances » ne veut pas dire exactement « 5 fois plus de légendaires » : les poissons communs restent dans le tirage, donc le gain réel est un peu plus faible. Il reste énorme sur les raretés hautes.
{% endhint %}

***

## Niveaux et récompenses

### L'XP

Chaque prise réussie donne **20 XP**, multipliés par ta canne, la zone bonus, un banc… (et divisés par deux hors zone). Le métier monte jusqu'au **niveau 50**.

Chaque niveau demande **100 XP de plus** que le précédent : 100 XP pour passer au niveau 2, 200 pour le niveau 3, 300 pour le niveau 4, etc. Il faut **122 500 XP** au total pour atteindre le niveau 50, soit environ 6 000 prises sans bonus, beaucoup moins avec une bonne canne. `/peche` affiche ton niveau et ton XP.

### Les récompenses de niveau

**À chaque niveau franchi** : 2 Bonbons Exp. M et **20 Écailles × ton nouveau niveau** (par exemple 400 Écailles en passant niveau 20). En plus, des paliers :

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

Chaque récompense n'est donnée **qu'une fois**, même si tu passes plusieurs niveaux d'un coup.

### Contrat du jour

Chaque jour, un contrat demande **15 prises**. Une fois atteint, valide-le avec `/peche contrats valider` (ou le bouton du menu) pour gagner **150 XP** et une **perle marine**. Il se renouvelle à **minuit, heure de Paris**, et ne se valide qu'une fois par jour sur tout le réseau.

***

## Trésors

À chaque prise, tu peux aussi remonter un **trésor**, en plus de ton poisson. Les chances de base sont multipliées par ta canne et la zone bonus :

| Trésor | Chance de base | À quoi ça sert |
| ------------------------ | :------------: | ------------------------------------------ |
| **Fragment des abysses** | 3 % | Matériau des cannes |
| **Perle marine** | 0,5 % | Matériau des cannes |
| **Autres trésors** | 2,5 % | Voir ci-dessous |

Les **autres trésors** sont tirés dans une liste : Bonbons Exp. M / L / XL, Super Bonbons, CT Aléatoires, Tickets Safari, Cristaux de Niveau, Cristaux d'EV, Cristaux IV Parfaits, **améliorations de canne**, Mega Gemmes, Œufs Shiny / Céleste / Légendaire, Objets Légendaires… et, très rarement, une **Master Ball**.

***

## Zones bonus, bancs et tournois

### Zones bonus

Une zone de pêche est **renforcée** à tour de rôle, et le bonus **change de zone toutes les heures**. L'eau de la zone renforcée prend une **couleur dorée**, et elle redevient bleue quand le bonus part ailleurs.

Bonus de base : **XP ×1,5**, **meilleurs poissons ×2**, **trésors ×1,5**. `/peche bonus` montre la zone active et le temps restant avant le prochain changement.

### Bancs de poissons

Toutes les **15 minutes**, un **banc** apparaît dans une zone : des remous sont visibles à la surface et ses coordonnées sont annoncées dans le chat. Pendant **5 minutes**, l'XP est **doublée** dans un rayon de **8 blocs** autour.

### Tournois

Un tournoi classe les pêcheurs pendant un temps limité, selon l'un de trois modes :

* **Poids** : la prise la plus lourde gagne ;
* **Quantité** : le plus de prises ;
* **Diversité** : le plus d'espèces différentes.

Il faut au moins **3 prises** pendant le tournoi pour être classé. Le podium reçoit des Écailles : **1 500 / 800 / 400**, versées même si le gagnant s'est déconnecté. `/peche tournoi` affiche le classement **en direct** (mis à jour toutes les deux secondes) et le temps restant, `/peche tournoi dernier` les résultats du précédent.

***

## Le Léviathan des Abysses

C'est l'événement communautaire de la pêche. Il se déroule en trois temps :

1. **La collecte.** Quand le staff l'ouvre, pêcher dans une zone peut te rapporter des **lots d'écailles de Léviator**.
2. **L'autel.** Offre tes lots à un **autel du Léviathan** (clique dessus). Tous les serveurs remplissent **le même autel**.
3. **Le combat.** Quand l'objectif commun est atteint, le **Léviathan des Abysses** est invoqué.

C'est un **boss en temps réel** (comme les [Boss](evenements/boss.md)) : tu le frappes et tu esquives ses attaques — **Marée abyssale**, **Geysers** et **Hydrocanon**. Ce n'est pas un combat Pokémon, et il ne se capture pas.

{% hint style="warning" %}
Les écailles de Léviator sont des **objets d'événement**, à ne pas confondre avec les **Écailles** de la boutique. Un lot reste lié à **sa** collecte : il ne servira pas pour la suivante.
{% endhint %}

`/peche communaute` affiche la progression de l'autel.

***

## Commandes

| Commande | Description |
| -------------------------------- | ------------------------------------------ |
| `/peche` | Menu principal : profil, niveau, Écailles, accès à tout |
| `/peche aide` | Guide « Comment jouer ? » en six étapes |
| `/peche carnet [page] [rareté]` | Ton carnet des 48 poissons, filtrable par rareté |
| `/peche sac` | Tes prises présentes dans l'inventaire |
| `/peche pnj` | Menu de l'Archiviste |
| `/peche pokemon [page]` | Historique des Pokémon pêchés |
| `/peche contrats [valider]` | Contrat du jour |
| `/peche zones` | Lieux de pêche et niveaux requis |
| `/peche bonus` | Zone bonus active et temps restant |
| `/peche tournoi [dernier]` | Tournoi en cours ou précédent |
| `/peche top` | Records de poids du réseau |
| `/peche communaute` | Progression de l'autel du Léviathan |

{% hint style="info" %}
**Conseils**

* Pêche **en zone**, et de préférence dans la **zone bonus** du moment ou sur un **banc**.
* Valide ton **contrat** tous les jours : 150 XP et une perle marine gratuits.
* Garde tes doublons : vendus à l'Archiviste, ils financent tes améliorations de canne.
* Pour chasser les légendaires et mythiques, prends une canne à fort bonus **meilleurs poissons** (Canne des marées, du grand large, du Léviathan) avec un **Appât raffiné**.
{% endhint %}
