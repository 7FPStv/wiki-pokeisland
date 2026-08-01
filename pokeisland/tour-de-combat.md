---
description: >-
  Quatre difficultés, des dresseurs PNJ à la chaîne, et ton équipe réelle pour
  seule arme. Une défaite et c'est fini.
icon: gopuram
---

# Tour de combat

La **Tour de combat** enchaîne des combats contre des dresseurs PNJ. Tu choisis une difficulté, tu es téléporté dans la salle du premier combat, et **le combat démarre tout seul à ton arrivée**. <kbd>**/tour**</kbd>

Si tu gagnes : récompense, soin de ton équipe, puis salle suivante. Si tu perds : éliminé, direction la sortie.

{% hint style="warning" %}
Contrairement à la [Battle Factory](battle-factory.md), tu combats avec ta **vraie équipe**. Prépare-la avant d'entrer — surtout ton bracelet Méga, que tu ne pourras plus équiper une fois dedans.
{% endhint %}

***

## Les quatre difficultés

| Difficulté | Combats | Niveau adverse | IA | Équipe exigée | Niveau max autorisé | Cooldown | Récompense finale |
| ------------- | ------- | -------------- | ----- | ------------- | ------------------- | -------- | ----------------- |
| **Facile** | 4 | 25-30 | 1-2/5 | 1 à 6 | 50 | 1 min | 2 500 |
| **Moyen** | 5 | 55-60 | 3-4/5 | 3 à 6 | 70 | 5 min | 10 000 |
| **Difficile** | 6 | 100 | 4-5/5 | 4 à 6 | 100 | 15 min | 40 000 |
| **Extrême** | 6 | 100 | 5/5 | 6 exactement | 100 | 1 h | 150 000 |

Chaque combat gagné rapporte aussi sa propre récompense, en plus du bonus de fin.

### Les dresseurs

Chaque difficulté a son casting, avec un boss au bout :

* **Facile** — Léo, Mina, Karl, puis le **Vétéran Sacha**
* **Moyen** — Elias, Nora, Bruno, Solène, puis la **Championne Iris**
* **Difficile** — Aldric, Vera, Kaelis, Ophélie, Maxence, puis le **Maître Dracen**
* **Extrême** — Élite Sylas, Élite Nyx, Élite Vulcan, Élite Marina, **Champion Orion**, puis le **Maître de la Tour**

{% hint style="danger" %}
En Extrême, les dresseurs jouent des équipes compétitives complètes (Métalosse Méga, Latios aux Lunettes Choix, Tyranocif Méga, Airmure, Leuphorie…). Le boss final a droit à **toutes** les mécaniques disponibles.
{% endhint %}

***

## Butin

Chaque combat gagné donne **au moins 1 objet**, et jusqu'à 3. La table change selon la difficulté :

* **Facile** — germes de Noigrume (les 7 couleurs), soins, et plus rarement des **Aromates de nature**
* **Moyen** — Joyaux de type (Glace, Insecte…) et consommables
* **Difficile** — **Fossiles** (Nautile, Dôme, Racine, Griffe, Crâne, Armure, Plaque, Plume, Mâchoire, Nageoire), Sachets Senteur, **Œufs Pokémon**
* **Extrême** — le haut du panier

***

## Méga et Téra

Les **Méga-Évolutions** et la **Térastallisation** sont autorisées dans la Tour, dans les deux camps. Le Dynamax et l'Ultra-Explosion, non.

Côté joueur, tu n'as rien à faire de spécial : tu combats avec ta vraie équipe et ton vrai bracelet, donc Mega Showdown t'affiche le bouton comme dans n'importe quel combat.

{% hint style="info" %}
Impossible de farmer une pierre Méga sur les PNJ : leurs objets tenus sont vidés au KO et leurs tables de butin sont coupées.
{% endhint %}

***

## Soin automatique

Ton équipe est soignée :

* **avant** chaque combat,
* **après** chaque victoire,
* **en sortant** de la tour.

Sans ça, la tour serait ingagnable dès le 3ᵉ combat. Tu ne peux pas entrer avec un Pokémon KO.

***

## Ce qui est bloqué pendant une ascension

* Tu es **immobilisé** pendant un combat (la caméra reste libre). Entre deux combats, tu peux bouger dans ta salle.
* **Aucune téléportation** : `/spawn`, `/home`, `/tp`, `/warp`, `/back`, `/rtp`, `/hub`, portails, perle de l'End, fruit chorus — tout est refusé.
* **Aucun objet** : clic droit, Poké Ball, potion, nourriture, seau, briquet, lit.
* **Aucun conteneur** : coffre, enderchest, PC Cobblemon.
* Pas de blocs cassés/posés, pas de monture.
* Commandes bloquées : `/spawn`, `/home`, `/kit`, `/pc`, `/heal`, `/ec`, `/back`, `/warp`… Restent autorisés : `/msg`, `/r`, et bien sûr `/tour`.
* Tu es **invulnérable** et tu ne perds pas de faim.

{% hint style="danger" %}
**Se déconnecter = défaite.** L'ascension est fermée, le cooldown est armé comme pour une défaite, et rien n'est reprenable. Les récompenses déjà gagnées sont conservées et te sont rendues à la reconnexion.

Seule exception : un redémarrage du serveur ne te coûte pas de tentative.
{% endhint %}

Une ascension inactive pendant 5 minutes est coupée automatiquement — mais un combat **en cours** n'est jamais interrompu, même s'il dure.

***

## Commandes

| Commande | Effet |
| -------------- | ------------------------------- |
| `/tour` | Ouvre le menu des difficultés |
| `/tour status` | État de ton ascension |
| `/tour quit` | Abandonne (le cooldown est armé) |
| `/tour top` | Classement |
| `/tour stats` | Tes statistiques |
