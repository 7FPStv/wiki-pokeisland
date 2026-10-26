---
hidden: true
description: >-
  Cache-cache en blocs, Pacman, Dé à Coudre, défilé de tenues… Le serveur
  Event accueille les mini-jeux des animations PokeIsland.
icon: gamepad
---

# Mini-jeux

Le [serveur Event](README.md) accueille les **mini-jeux** joués pendant les animations : cache-cache, course, Pacman, concours de tenues, tournoi Cobblemon…

***

## Sur le serveur Event

Sur le serveur Event, tu joues en mode **Aventure** : pas de dégâts d'environnement, pas de faim, et aucun objet ne se jette ni ne se ramasse en dehors des parties.

{% hint style="info" %}
Pendant une partie, salle d'attente comprise, seules les commandes des mini-jeux fonctionnent.
{% endhint %}

***

## Rejoindre une partie

Chaque mini-jeu a sa commande :

* `/<jeu> join <arène>` pour rejoindre, par exemple `/sumo join 01` ;
* `/<jeu> leave` pour quitter ;
* `/<jeu> list` pour voir les arènes.

`/mj help` (ou `/minijeux help`) affiche l'aide générale.

La plupart des jeux **démarrent tout seuls** : un compte à rebours se lance dès que le nombre minimum de joueurs est atteint. Pacman, Dress To Impress et le Tournoi Cobblemon sont lancés par l'animateur.

***

## Les mini-jeux

| Mini-jeu | Commande | Joueurs |
| ----------------------------- | ---------------------------------- | ------- |
| **Hide and Seek** (cache-cache) | `/hns join` | 4 minimum |
| **Pacman** | `/pacman join 01` | 2 minimum |
| **Dress To Impress** | `/dress join` | 2 minimum |
| **Run** | `/run join 01` | 2 à 64 |
| **Dé à Coudre** | `/deacoudre join 01` | 2 à 64 |
| **Sumo** | `/sumo join 01` | 2 à 20 |
| **Hold The Color** | `/color join 01` ou `02` | 2 à 64 |
| **Anvil Drop** | `/anvil join 01` ou `02` | 2 à 64 (arène 01), 2 à 12 (arène 02) |
| **Squid Express** | `/squid help` | 2 à 64 |
| **Tournoi Cobblemon** | `/tournoi join <nom>` | lancé par l'animateur |
| **Morpion** | `/morpion play` | seul, contre un bot |

### Hide and Seek

Un cache-cache où les cachés **se déguisent en blocs**. Trois cartes : **Village japonais**, **Village Pokémon** et **Château**.

1. **30 secondes** pour se cacher : choisis ton bloc, puis accroupis-toi pour te figer et te fondre dans le décor. Les chercheurs, eux, attendent aveuglés.
2. **5 minutes** de chasse : un coup de chercheur retire une vie à un caché. Les cachés ont **3 vies** ; à zéro, tu passes chercheur.
3. Les cachés gagnent s'il en reste à la fin du temps, les chercheurs s'ils les ont tous trouvés.

### Pacman

Les joueurs sont répartis entre **Pacman** et **fantômes**.

* **Pacman** a **3 vies**, une vitesse accrue et une plume **Dash** (un élan de 5 blocs, toutes les 20 secondes). Il doit ramasser les gommes de l'arène.
* Les **fantômes** le chassent à l'épée : chaque touche lui coûte une vie.
* La **Super Gomme** permet à Pacman de dévorer les fantômes pendant quelques secondes. Méfie-toi des **fausses gommes**, qui le piègent.

Pacman gagne s'il ramasse **90 %** des gommes, les fantômes s'ils lui prennent toutes ses vies.

### Dress To Impress

Un concours de tenues en quatre temps :

1. **Vote du thème** (30 secondes) parmi Team Rocket, Légendaire, Champion d'Arène, Halloween, Noël, Royauté, Cute, Mage, Apocalypse ou Plage.
2. **Préparation** (5 minutes) : `/dress` ouvre le dressing. Tu peux sauvegarder tes tenues avec `/outfit save <nom>` et les recharger avec `/outfit load <nom>`.
3. **Défilé** : chaque candidat défile 15 secondes pendant que les autres lui donnent de 1 à 5 étoiles.
4. **Résultats** : le total des étoiles désigne le podium.

### Run

Une course en **15 niveaux** : atteins la zone d'arrivée avant la fin du chrono (de 35 secondes au premier niveau à 100 secondes au dernier). Ceux qui n'arrivent pas à temps sont éliminés. Une chute te renvoie au départ du niveau.

### Dé à Coudre

Chacun son tour, saute du plongeoir dans la piscine : tu as **10 secondes**. Réussi, l'eau devient un bloc de ta couleur ; raté, tu perds ta **seule vie**. Le classement se fait au nombre de sauts réussis.

### Sumo

Pousse les autres hors de la plateforme avec ton bâton : les coups ne font pas de dégâts, ils repoussent. Le recul **augmente toutes les 20 secondes**, jusqu'au double. Le dernier debout gagne.

### Hold The Color

Le sol se couvre de blocs de couleur, puis une couleur est annoncée : reste dessus, tous les autres blocs disparaissent. Chaque manche est plus courte que la précédente, de 6 secondes jusqu'à 2. Le dernier survivant gagne.

### Anvil Drop

Esquive les enclumes qui tombent du ciel, de plus en plus nombreuses (de 10 à 60 par vague). Tu as **3 vies**. Le dernier survivant gagne.

### Squid Express

Trois épreuves rapides enchaînées : **Soleil**, **Salles** (5 vagues de 12 secondes) et **Bombe**. Gagner rapporte **110 coins**, monter sur le podium **60**, et participer **15**.

### Tournoi Cobblemon

Un tournoi à élimination organisé par l'animateur : tu choisis tes Pokémon dans une sélection imposée (draft), puis tu les personnalises avant de combattre. Inscription avec `/tournoi join <nom>` pendant l'ouverture des inscriptions.

### Morpion

Pour patienter entre deux parties : un morpion contre un bot, `/morpion play`.

***

## Les coins

Chaque partie rapporte des **coins** (🪙), plus si tu montes sur le podium. Ils sont **communs à tous les mini-jeux**, mais séparés de tes PokéCoins.

| Commande | Effet |
| ------------------------------- | ------------------------ |
| `/money` | Ton solde de coins |
| `/money top` | Les plus riches en coins |
| `/money pay <joueur> <montant>` | Donner des coins |
| `/shop` | Boutique d'effets cosmétiques de lobby (auras, traînées, double saut…) |

***

## Classements

* Chaque jeu a son classement : `/<jeu> top wins`, par exemple `/sumo top wins`.
* `/historique` retrace les parties jouées et tes résultats.
* Pendant une animation, l'animateur peut ouvrir un **classement d'event** : chaque partie rapporte **5 points** au 1ᵉʳ, **3** au 2ᵉ et **1** au 3ᵉ, cumulés jusqu'à sa clôture. Consulte-le avec `/classement voir <nom>`. Le Morpion n'y compte pas.
