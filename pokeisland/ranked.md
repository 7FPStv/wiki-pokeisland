---
description: >-
  Le PvP compétitif de PokeIsland : file d'attente, ELO, saisons, et une
  boutique réservée aux meilleurs.
icon: ranking-star
---

# Ranked 1v1

Le **Ranked** est le mode compétitif du serveur. Tu rejoins une file d'attente, le serveur te trouve un adversaire de niveau proche, et vous vous affrontez en combat Cobblemon officiel. <kbd>**/ranked**</kbd>

***

## Les trois files

| File | Commande | Classé ? | Restrictions d'équipe |
| ------------- | ------------ | -------- | --------------------- |
| **Ranked** | `/ranked` | Oui (ELO) | Oui |
| **Unranked** | `/unranked` | Non (stats gardées) | Oui |
| **Libre** | `/free` ou `/libre` | Non | **Non** |

Les trois existent aussi en **2v2** (combats Doubles), avec un ELO séparé du 1v1.

{% hint style="info" %}
La file est **partagée sur tout le réseau**. Tu peux faire la queue depuis n'importe quel serveur : tu seras transféré vers le serveur des arènes, puis renvoyé chez toi à la fin du match.
{% endhint %}

***

## Comment se déroule un match

1. Tu rejoins la file. Le matchmaking cherche un adversaire toutes les secondes.
2. Plus tu attends, plus la fenêtre d'ELO s'élargit :

| Attente | Écart d'ELO toléré |
| --------- | ------------------ |
| 0 s | ± 100 |
| 30 s | ± 200 |
| 60 s | ± 350 |
| 120 s | n'importe qui |

3. Adversaire trouvé : **5 secondes** de compte à rebours, puis téléportation en arène.
4. **Team Preview** : tu vois l'équipe adverse et ses talents avant de jouer.
5. Le combat se joue en **GEN 9 Singles**, tous les Pokémon ramenés au **niveau 50**.
6. À la fin, tu es renvoyé là où tu étais.

Les équipes sont **soignées avant le combat**, et les **objets du sac (potions…) sont bloqués** pendant le match en Ranked et Unranked.

Un match qui dépasse **30 minutes** est déclaré nul.

***

## Le système d'ELO

* Tu démarres à **100 ELO**.
* Facteur K : **32** (une victoire contre plus fort rapporte gros).
* L'ELO ne descend jamais sous **0**.

### Les rangs

| Rang | ELO minimum |
| ---------------- | ----------- |
| Bronze | 0 |
| Argent | 90 |
| Or | 180 |
| Platine | 280 |
| Diamant | 380 |
| **Master** | 500 |
| **Champion** | 650 |

Les passages de rang à partir de **Master** sont annoncés à tout le serveur.

***

## Restrictions d'équipe (Ranked)

Ces règles sont vérifiées **avant** que tu rejoignes la file.

| Règle | Valeur |
| ------------------------------ | ----------- |
| Taille d'équipe | 1 à 6 |
| Niveau max | 100 (ramené à 50 en combat) |
| Pokémon **restreints** max | 2 |
| **Fabuleux** max | 0 |
| **Fusions** max | 1 |
| Doublons de Pokémon | Interdits |
| Doublons d'objets tenus | Interdits |
| **Dynamax** | Interdit |
| **Térastallisation** | Interdite |

**Espèces bannies** : Mew, Celebi, Jirachi, Deoxys, Phione, Manaphy, Darkrai, Shaymin, Arceus, Victini, Keldeo, Meloetta, Genesect, Diancie, Hoopa, Volcanion, Magearna, Marshadow, Zeraora, Meltan, Melmetal, Zarude, Pecharunt.

{% hint style="info" %}
La file **Libre** (`/free`) n'applique **aucune** de ces restrictions. C'est là que tu testes tes fusions et tes équipes farfelues.
{% endhint %}

***

## Les saisons

Le Ranked fonctionne par **saisons**. À la fin de chaque saison :

1. un instantané du classement est pris et les **récompenses de fin de saison** sont versées,
2. les ELO sont remis à zéro en **soft reset** : ton nouvel ELO = 100 + (ton ancien ELO − 100) ÷ 2.

Tu gardes donc une partie de ton avance, sans repartir de zéro.

{% hint style="warning" %}
Entre deux saisons, la file **Ranked est fermée**. Unranked et Libre restent ouvertes.
{% endhint %}

***

## Anti-abus et pénalités

* **Déconnexion en match = défaite**, plus **5 ELO de pénalité supplémentaire**.
* Un joueur **AFK plus de 2 minutes** est sorti de la file.
* Maximum **50 matchs classés par jour contre le même joueur**.

***

## La boutique Ranked

Les combats te rapportent deux monnaies : **ranked** et **unranked**. Elles s'échangent dans une boutique dédiée. `/shop`

Certains articles sont **verrouillés par rang** et **limités en quantité** :

| Article | Monnaie | Prix | Rang requis | Limite |
| ------------------- | -------- | ---- | ------------ | ------ |
| **Master Ball** | ranked | 100 | **Champion** | 1 |
| **Pierre Shiny** | ranked | 150 | **Master** | 1 |
| Super Bonbon | unranked | 8 (ou 5 en ranked) | — | illimité |
| Pierres d'évolution | unranked | 25 (ou 15 en ranked) | — | illimité |

La boutique contient **toute la gamme des objets d'évolution** Cobblemon.

{% hint style="success" %}
Les limites sont **cumulatives** : monter de rang débloque des achats supplémentaires, sans effacer ceux déjà faits.
{% endhint %}

***

## Commandes

| Commande | Effet |
| --------------- | ------------------------------------- |
| `/ranked` | Menu et file classée |
| `/unranked` | File non classée (avec restrictions) |
| `/free` | File libre (sans restrictions) |
| `/rank [joueur]` | Ton rang ou celui d'un autre |
| `/toprank` | Classement des meilleurs joueurs |

{% hint style="danger" %}
Taper `/endbattle` ou `/forfeit` pendant un match compte comme un **abandon** : tu es déclaré perdant.
{% endhint %}
