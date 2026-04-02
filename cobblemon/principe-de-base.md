---
icon: "book"
description: "Tout comprendre à Cobblemon : starter, Poké Balls, Pokédex, capture, EV/IV, évolution et Mega/Téra."
---

<div align="center">
  <img src="https://commons.wikimedia.org/wiki/Special:FilePath/Pok%C3%A9%20Ball%20icon.svg" alt="Poké Ball" width="84">
</div>

# Cobblemon : principes de base

Cobblemon, c’est le mod Pokémon qui transforme Minecraft en monde Pokémon. Sur **PokeIsland**, tu combines tout ça avec nos systèmes de progression (énergie, rangs, PokéBuilder, badges, etc.).

Cette page est pensée pour les joueurs qui découvrent Cobblemon : pas besoin de connaître le “back-end”, juste le **comment jouer**.

---

## Réglages de contrôles (recommandés)
L’idée : que tes actions Cobblemon soient “naturelles”, comme dans le jeu.

- **Vise + lance une Poké Ball** : garde la ball en main, puis utilise l’action d’item du jeu (souvent **clic droit / Interagir**) sur le Pokémon.
- **Interagir / ouvrir les menus** : utilise la **souris** pour sélectionner les options dans les interfaces.
- **Pokédex** : une fois que tu as l’objet, ouvre-le depuis ton inventaire pour afficher tes entrées.
- **PokéBuilder** : utilise la commande `/pokebuilder` pour accéder aux modules (EV/IV, nature, capacité, pokeball, etc.).
- **Esc** : pratique pour fermer les interfaces quand tu as fini.

Si tu as l’habitude de Minecraft “vanilla”, tu seras déjà à l’aise.

## 1. Ton starter (le début de l’aventure)
Quand tu rejoins le serveur pour la première fois, tu arrives sur le **Spawn** et tu choisis ton **starter** Cobblemon.

Si tu veux le chemin complet, regarde : [`Premier pas`](../tutoriel/premier-pas.md).

---

## 2. L’essentiel à savoir sur les Poké Balls
Pour capturer un Pokémon, tu as besoin d’une **Poké Ball**.

Sur PokeIsland, chaque Poké Ball consomme aussi de l’**énergie** (voir la page `Énergie` si tu veux comprendre la mécanique derrière).

Exemples de coût en énergie (par ball) :

| Poké Ball | Coût énergie |
|---|---:|
| `cobblemon:poke_ball` | 2 |
| `cobblemon:great_ball` | 3 |
| `cobblemon:ultra_ball` | 5 |
| `cobblemon:safari_ball` | 3 |
| `cobblemon:heavy_ball` | 4 |
| `cobblemon:master_ball` | 50 |

---

## 3. Capturer : en mode simple
1. Repère un Pokémon dans le monde.
2. Prépare une Poké Ball dans ta main (et garde en tête ton énergie).
3. Lance la Poké Ball : si ça réussit, le Pokémon part dans ta collection.

Conseil : si tu veux capturer “en chaîne”, assure-toi d’avoir de quoi **recharger ton énergie** (packs).

---

## 4. Le Pokédex : ton compteur d’avancement
Le **Pokédex** sert à suivre ta progression : plus tu rencontres/captures, plus ton Pokédex se remplit.

Sur PokeIsland, le Pokédex est aussi lié à la progression de ton personnage : il débloque des récompenses et contribue à ton avancée (notamment via ton évolution “dresseur”).

Quand tu as le Pokédex :
- interagis avec l’objet **Pokédex** dans ton inventaire pour accéder à l’interface,
- et laisse Cobblemon faire le reste au fil de tes captures.

---

## 5. Donner/équiper un objet (Held Item)
Sur Cobblemon, un Pokémon peut porter un **objet tenu** (ex : une pierre, un item de combat, etc.).

En pratique :
- ouvre la fiche de ton Pokémon,
- et dans l’interface, cherche l’option pour définir l’**objet tenu** (si une évolution/stratégie dépend d’un item, c’est là que tu gères).

Sur PokeIsland, tu peux aussi utiliser **PokéBuilder** pour aller plus loin (IV/EV, nature, capacité, etc. selon les modules). Pour l’ouvrir, le serveur utilise la commande :
`/pokebuilder`

---

## 6. Évoluer : transforme tes Pokémon (sans tricher)
Les évolutions dépendent de la condition demandée :
- **niveau** (parfois avec un niveau précis),
- **objet** (pierres / items spécifiques),
- ou des conditions plus “spéciales” (selon les Pokémon).

Astuce : dans la fiche du Pokémon, si une évolution est disponible, tu verras l’option correspondante.

---

## 7. EV et IV : le duo secret (et pas si compliqué)
### IV (ce que tu “naîs” avec)
Les **IV** sont des valeurs cachées (entre 0 et 31 par statistique) qui influencent ton potentiel.

Sur PokeIsland, PokéBuilder permet d’améliorer/monter certaines IV, avec des limites :
- **IV max par stat** : `31`
- **IV total max** : `186`
- **IVs par jour** : `186`

### EV (ce que tu “entraînes”)
Les **EV** sont liés à l’entraînement (captures/batailles/etc. selon le système).

Sur PokeIsland, les limites sont :
- **EV total max** : `510`
- **EV max par statistique** : `252`
- **EVs par jour** : `510`

### Où entraîner tes EV sur PokeIsland ?
Les EV sont principalement liés à nos **Safaris EV** :
- **Rock Safari** : Attaque / Attaque spéciale / Vitesse
- **Fire Safari** : PV / Défense / Défense spéciale

Guide : [`Safari` dans PokéWorld](../pokeisland/pokeworld/safari.md).

### La méthode “joueur”
Si tu veux progresser efficacement :
1. Capture/entraîne un Pokémon.
2. Planifie une répartition EV (selon ce que tu veux : attaque, défense, vitesse…).
3. Finalise avec PokéBuilder si besoin (IV/EV/nature selon ton cas).

---

## 8. Mega / Téra / Z-Moves : quand la bataille devient… cosmique
Pour Méga, Téra, Z-Moves et Dynamax, tout se joue dans les mécaniques de bataille gérées par le mod MegaShowdown.

Page dédiée : [`MegaShowdown (Méga/Téra/Z/Dynamax)`](./mega-showdown.md).

---

## 9. Mini-checklist (pour ne rien oublier)
- Starter choisi.
- Poké Balls préparées.
- Captures régulières (et énergie gérée).
- Pokédex rempli.
- Objet tenu bien installé.
- Évolution quand disponible.
- EV/IV optimisés progressivement.
- Mega/Téra pour passer en mode “baston sérieuse”.


