---
description: >-
  Tout ce qu'il faut comprendre pour arrêter de perdre : types, statistiques,
  statuts, et comment lire l'interface de combat.
icon: swords
---

# Guide du combat

Tu captures, tu combats, tu perds, tu ne comprends pas pourquoi. Cette page est là pour ça.

***

## 1. Lancer un combat

Il y a plusieurs façons de te battre sur PokeIsland :

| Contre                                                   | Comment                                                                  |
| -------------------------------------------------------- | ------------------------------------------------------------------------ |
| Un Pokémon sauvage                                       | Envoie ton Pokémon dessus                                                |
| Un [dresseur PNJ](dresseurs-sauvages.md)                 | Il te défie à vue                                                        |
| Un [champion d'arène](../pokeisland/pokeworld/arenes.md) | Tu vas le trouver dans son arène                                         |
| Un autre joueur                                          | [`/duel`](../pokeisland/duel.md) ou [`/ranked`](../pokeisland/ranked.md) |

***

## 2. La table des types

C'est **la** chose à connaître. Une attaque du bon type fait **2× de dégâts**, du mauvais type **0,5×**, et parfois **0** (immunité).

**Les faiblesses les plus utiles à retenir :**

| Type attaqué | Faible contre                    | Résiste à                                   |
| ------------ | -------------------------------- | ------------------------------------------- |
| **Feu**      | Eau, Sol, Roche                  | Feu, Plante, Glace, Insecte, Acier, Fée     |
| **Eau**      | Plante, Électrik                 | Feu, Eau, Glace, Acier                      |
| **Plante**   | Feu, Glace, Poison, Vol, Insecte | Eau, Plante, Électrik, Sol                  |
| **Électrik** | Sol                              | Électrik, Vol, Acier                        |
| **Roche**    | Eau, Plante, Combat, Sol, Acier  | Normal, Feu, Poison, Vol                    |
| **Sol**      | Eau, Plante, Glace               | Poison, Roche _(immunisé Électrik)_         |
| **Vol**      | Électrik, Glace, Roche           | Plante, Combat, Insecte _(immunisé Sol)_    |
| **Dragon**   | Glace, Dragon, Fée               | Feu, Eau, Plante, Électrik                  |
| **Spectre**  | Spectre, Ténèbres                | Poison, Insecte _(immunisé Normal, Combat)_ |
| **Acier**    | Feu, Combat, Sol                 | Beaucoup de choses _(immunisé Poison)_      |

**Les trois immunités qui font perdre des combats :**

* Sol → **aucun effet** sur un Pokémon Vol
* Normal et Combat → **aucun effet** sur un Pokémon Spectre
* Électrik → **aucun effet** sur un Pokémon Sol

{% hint style="success" %}
Le mod [Battle Extras](/broken/pages/v86act9NEoOANf7IruBj) affiche des **icônes de type** en combat : tu vois directement si ton attaque est efficace avant de la lancer.
{% endhint %}

***

## 3. Les six statistiques

| Stat                 | À quoi elle sert                           |
| -------------------- | ------------------------------------------ |
| **PV**               | Combien de dégâts tu encaisses avant le KO |
| **Attaque**          | Puissance de tes attaques **physiques**    |
| **Défense**          | Résistance aux attaques physiques          |
| **Attaque Spéciale** | Puissance de tes attaques **spéciales**    |
| **Défense Spéciale** | Résistance aux attaques spéciales          |
| **Vitesse**          | Qui attaque en premier                     |

{% hint style="warning" %}
**Physique ou spéciale ?** Ça dépend de l'attaque, pas du type. Un Pokémon avec une grosse Attaque et des capacités spéciales ne sert à rien. Vérifie toujours que le moveset colle au profil.
{% endhint %}

La **nature** modifie deux stats (+10 % sur l'une, −10 % sur l'autre). Les **IV** et **EV** ajoutent le reste — voir [Principe de base](principe-de-base.md) et le [PokéBuilder](../pokeisland/pokebuilder.md).

***

## 4. Les statuts

| Statut           | Effet                                                     |
| ---------------- | --------------------------------------------------------- |
| **Brûlure**      | Dégâts par tour + **Attaque divisée par 2**               |
| **Poison**       | Dégâts par tour                                           |
| **Poison grave** | Dégâts par tour, **de plus en plus forts**                |
| **Paralysie**    | **Vitesse divisée par 2** + 25 % de chance de ne pas agir |
| **Sommeil**      | Ne peut rien faire pendant 1 à 3 tours                    |
| **Gel**          | Ne peut rien faire jusqu'au dégel                         |

Un Pokémon ne peut avoir **qu'un seul statut** à la fois. C'est pour ça qu'endormir un adversaire le protège… de la brûlure.

Les **statuts volatils** (confusion, accroc, terreur, protection) disparaissent quand le Pokémon change de place.

***

## 5. Les changements de stats

En combat, une capacité peut monter ou baisser une stat, de −6 à +6 crans.

| Crans | Multiplicateur |
| ----- | -------------- |
| +1    | ×1,5           |
| +2    | ×2             |
| +6    | ×4             |
| −1    | ×0,66          |
| −2    | ×0,5           |
| −6    | ×0,25          |

Ces changements **disparaissent** quand tu rappelles ton Pokémon. C'est le prix à payer pour se protéger.

***

## 6. Lire l'interface

Grâce aux mods installés sur PokeIsland, ton interface de combat t'affiche :

* les **icônes de type** de chaque attaque et de chaque Pokémon,
* les **crans de stats** en cours (+1 Attaque, −2 Défense…),
* une **pop-up de talent** quand un talent se déclenche,
* la **météo** et le **terrain** actifs,
* les **pièges au sol** (Piège de Roc, Picots…),
* les **écrans** (Mur Lumière, Protection),
* les **statuts volatils** en icônes,
* une **infobulle détaillée** au survol d'une attaque (puissance, précision, PP).

***

## 7. Les erreurs de débutant

{% hint style="danger" %}
**Foncer avec un seul Pokémon.** Une équipe, c'est six Pokémon aux types complémentaires. Si tout ton roster est faible à l'Eau, un seul Léviator te détruit.

**Ignorer la Vitesse.** Frapper en premier vaut souvent mieux que frapper fort.

**Ne jamais switcher.** Rappeler un Pokémon coûte un tour, mais évite un KO. C'est presque toujours rentable.

**Ne pas soigner entre deux combats.** Un Pokémon à 20 % de PV est un Pokémon mort.

**Oublier les PP.** Chaque attaque a un nombre d'utilisations limité. À court de PP, ton Pokémon se réduit à Lutte.
{% endhint %}

***

## 8. Pour aller plus loin

* [Objets tenus et évolutions](pokemon/) — l'objet tenu change souvent tout
* [Capacités : CT & DT](capacites-ct-dt.md) — construire un vrai moveset
* [Mega Showdown](mega-showdown.md) — Méga, Téra, Z-Moves et Dynamax
* [PokéBuilder](../pokeisland/pokebuilder.md) — optimiser IV, EV et nature
* [Ranked](../pokeisland/ranked.md) — quand tu te sens prêt pour le PvP sérieux
