---
description: >-
  Le PvP compétitif de PokeIsland : file d'attente, ELO, saisons, et une
  boutique réservée aux meilleurs.
icon: ranking-star
---

# Ranked

Le **Ranked** est le mode compétitif du serveur. Tu rejoins une file d'attente, le serveur te trouve un adversaire de niveau proche, et vous vous affrontez en combat Cobblemon officiel. <kbd>**/ranked**</kbd>

***

## Les trois files

| File | Commande | Classé ? | Restrictions d'équipe |
| ------------- | ------------ | -------- | --------------------- |
| **Ranked** | `/ranked` | Oui (ELO) | Oui |
| **Unranked** | `/unranked` | Non (stats gardées) | Non (sac bloqué) |
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
5. Le combat se joue en **GEN 9 Singles** (Doubles en 2v2), tous les Pokémon ramenés au **niveau 100**.
6. À la fin, tu es renvoyé là où tu étais.

Les équipes sont **soignées avant le combat**, et les **objets du sac sont bloqués** pendant le match en Ranked et Unranked : Potions, Rappels, Huiles, Baies, objets X… Si tu essaies, l'objet n'est pas consommé.

{% hint style="warning" %}
Ton équipe est vérifiée **en entrant dans la file ET au début du combat**. Échanger un Pokémon interdit pendant l'attente te fait **perdre par forfait**.
{% endhint %}

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

## Les règles (Ranked)

Le Ranked suit les règles de **Smogon**, la référence du Pokémon compétitif (format *National Dex OU*), avec quelques ajustements propres à PokeIsland. Elles s'appliquent au Ranked 1v1 et 2v2.

### En équipe

| Règle | Valeur |
| ---------------------------- | --------------------------- |
| Taille d'équipe | 1 à 6 |
| Niveau | ramené à **100** en combat |
| **Même Pokémon en double** | Interdit (*Species Clause*) |
| Même objet tenu en double | Autorisé |
| **Méga-évolution** | Autorisée (sauf les Méga-Gemmes bannies) |
| **Capacités Z** | Autorisées |
| **Fusions** | **Toutes interdites** |
| Pokémon **Gigamax** | Interdits |

### En combat

* **Clause de sommeil** : un seul Pokémon adverse endormi à la fois. Une 2ᵉ attaque de sommeil échoue.
* **Pas de Téracristallisation**.
* **Pas de Dynamax**.
* **Pas d'objets du sac**.

### Pokémon interdits

Smogon n'interdit pas les légendaires en bloc : il bannit ceux qui sont trop forts, **forme par forme**.

**Légendaires majeurs** : Mewtwo, Lugia, Ho-Oh, Kyogre, Groudon, Rayquaza, Dialga, Palkia, Giratina, Arceus (toutes formes), Reshiram, Zekrom, Xerneas, Yveltal, Solgaleo, Lunala, Zacian, Éthernatos, Koraidon, Miraidon, Terapagos.

**Toutes les formes** : Genesect, Magearna, Superdofin.

**Formes précises seulement** :

| Interdit | Reste autorisé |
| ----------------------------------------------- | ------------------------- |
| Deoxys forme Normale, Attaque, Vitesse | Deoxys forme Défense |
| Shaymin forme Céleste | Shaymin forme Terrestre |
| Démétéros forme Avatar | Démétéros forme Totémique |
| Kyurem Noir, Kyurem Blanc | Kyurem |
| Zygarde forme 50 %, forme Parfaite | Zygarde forme 10 % |
| Necrozma Crinière du Couchant, Ailes de l'Aurore, Ultra | Necrozma |
| Zamazenta forme Couronnée | Zamazenta |
| Shifours Style Poing Final | Shifours Style Mille Poings |
| Sylveroy Cavalier du Froid, Cavalier d'Effroi | Sylveroy |
| Ursaking Lune Vermeille | Ursaking |
| Darumacho de Galar | Darumacho |
| Ogerpon Masque du Fourneau | les autres masques |

**Autres** : Munja, Cancrelove, Mandrillon, Marshadow, Melmetal, Hydragon, Lanssorien, Regieleki, Spectreval, Farfurex, Cléopsytra, Courrousinge, Scalpereur, Flotte-Mèche, Hotte-de-Fer, Glaivodo, Gromago, Baojian, Yuyu, Serpente-Eau.

**PokeIsland** : **Didier** et **toutes les fusions** du [Fusionneur](fusionneur.md).

### Objets, attaques et talents interdits

| Type | Interdits |
| -------- | --------- |
| **Objets** | Roche Royale, Croc Rasoir, Vive Griffe, Poudre Claire, Encens Doux, Bouclier Rouillé, et les Méga-Gemmes d'Alakazam, Tortank, Braségali, Ectoplasma, Kangourex, Lucario, Métalosse et Drattak |
| **Attaques** | Abîme, Glaciation, Guillotine, Empal'Korne (K.O. en un coup), Reflet, Lilliput (esquive), Assistance, Relais, Hommage Posthume, Queulonage |
| **Talents** | Marque Ombre, Piège Sable, Lunatique, Rassemblement, Voile Sable, Rideau Neige |

{% hint style="info" %}
L'**Unranked** n'applique pas ces règles d'équipe (seul le sac y est bloqué), et la file **Libre** (`/free`) n'applique **rien du tout**. C'est là que tu testes tes fusions et tes équipes farfelues.
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
| `/unranked` | File non classée |
| `/free` | File libre (sans restrictions) |
| `/rank [joueur]` | Ton rang ou celui d'un autre |
| `/toprank` | Classement des meilleurs joueurs |

{% hint style="danger" %}
Taper `/endbattle` ou `/forfeit` pendant un match compte comme un **abandon** : tu es déclaré perdant.
{% endhint %}
