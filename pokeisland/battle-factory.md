---
description: >-
  Enchaîne des combats avec des Pokémon de location que tu ne choisis pas
  vraiment : la Battle Factory teste ton sens tactique, pas ton élevage.
icon: dice
---

# Battle Factory

Dans la **Battle Factory**, tu ne combats **jamais** avec tes propres Pokémon. Le serveur te propose un tirage de Pokémon de **location**, tu en gardes une partie, et tu enchaînes les combats contre des dresseurs PNJ. <kbd>**/bf**</kbd>

{% hint style="info" %}
Les Pokémon de location n'entrent **jamais** dans ton équipe réelle ni dans ton PC. Ils vivent dans une équipe temporaire : une déconnexion ou un crash ne peut pas te les faire garder.
{% endhint %}

***

## Le format d'une série

| Règle | Valeur |
| ----------------------------- | -------------------------- |
| Pokémon proposés au tirage | 6 |
| Pokémon que tu gardes | 3 |
| Combats par manche | 3 |
| Manches maximum | 3 (soit 9 combats) |
| Niveau imposé | 50 pour tout le monde |
| IV des Pokémon de location | 31 partout par défaut |
| Niveau de l'IA adverse | 3/5 |

Les deux équipes sont **refabriquées avant chaque combat** : tu repars donc toujours à pleine vie, comme dans une vraie Battle Factory.

***

## L'échange après victoire

C'est le cœur du mode : après chaque combat gagné, tu peux **échanger 1 de tes Pokémon contre 1 de ceux du dresseur vaincu**.

* Tu vois l'équipe adverse **avant** le combat : à toi d'anticiper ce que tu voudras lui piquer.
* Tu as **30 secondes** pour choisir. Passé ce délai, aucun échange n'est fait.
* 1 échange maximum par combat gagné.

Bien joué, ta première équipe de fortune se transforme en machine de guerre au fil de la série.

***

## Difficulté croissante

La difficulté monte avec ta série : plus tu enchaînes les victoires, plus les dresseurs adverses tapent dans des paliers de Pokémon élevés.

En revanche, **aucun gimmick n'est actif** en Battle Factory : pas de Méga, pas de Térastallisation, pas de Dynamax. La montée en puissance passe uniquement par les paliers et les échanges.

***

## Récompenses

**Butin** : chaque victoire donne **au moins 1 objet**, et jusqu'à 3.

Ce que tu peux décrocher, du plus commun au plus rare :

* **Commun** — sucreries (Fraise, Cœur, Baie, Trèfle, Fleur, Étoile, Ruban en Sucre), herbes (Mental, Pouvoir, Blanche), pommes, objets d'évolution (Peau Métal, Améliorator, CD Douteux, Griffe/Croc Rasoir, Roche Royale, Dent/Écaille Océan…)
* **Peu commun** — objets tenus compétitifs : Bandeau/Mouchoir/Lunettes Choix, Veste de Combat, Orbe Vie, Carton Rouge, Sac Fuite, Assurance Échec, Vulné Assurance, Lumargile, Spray Gorge…
* **Rare** — Cristaux EV (PV, Attaque, Défense, Att. Spé, Déf. Spé, Vitesse) et Œuf Pokémon
* **Très rare** — Énergie Booster, **Œuf Shiny**, Pierre Scintillante Claire / Sombre

**Paliers de manche** (en PokéCoins) :

| Victoires cumulées | Récompense |
| ------------------ | ---------- |
| 3 (fin de manche 1) | 5 000 |
| 6 (fin de manche 2) | 15 000 |
| 9 (fin de manche 3) | 40 000 |

Tu gagnes aussi de l'**XP Dresseur** : 20 par victoire, +100 par palier.

{% hint style="success" %}
Si tu te déconnectes avant d'avoir touché une récompense, elle t'est livrée à ton retour.
{% endhint %}

***

## Limites et cooldown

* **Cooldown global : 24 h.** Il est armé quelle que soit l'issue — victoire, défaite, abandon **et déconnexion**. Se déconnecter en pleine série ne rend donc pas l'essai gratuit.
* Ce cooldown est stocké en base : il survit à un redémarrage et vaut sur **tous les serveurs**.
* Un petit délai anti-spam de 30 s s'ajoute entre deux séries.

***

## Ce qui est bloqué pendant une série

Une série doit se jouer sans aide extérieure. Pendant toute la durée de ta run :

* tu es **figé** pendant un combat ;
* impossible d'utiliser un objet, d'en jeter ou d'en ramasser ;
* impossible d'ouvrir un coffre ou un PC ;
* impossible de casser/poser des blocs, de monter sur une monture, de te téléporter ;
* les commandes sont bloquées, sauf : `/bf`, `/battlefactory`, `/quit`, `/abandon`, `/msg`, `/r`.

Tu es **invulnérable** et tu ne perds pas de faim : un creeper ne doit pas décider de l'issue d'un combat.

***

## Classement

Le classement Battle Factory est **partagé entre tous les serveurs** du réseau. Il affiche le top 10.

***

## Commandes

| Commande | Effet |
| ---------------- | ------------------------------------ |
| `/bf` | Ouvre le menu et lance une série |
| `/bf status` | État de ta série en cours |
| `/bf quit` | Abandonne (le cooldown est armé) |
| `/bf top` | Classement |
