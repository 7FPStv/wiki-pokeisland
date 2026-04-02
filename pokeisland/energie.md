---
icon: transformer-bolt
---

# Energie

<div align="center">
  <img src="https://commons.wikimedia.org/wiki/Special:FilePath/Lightning_Bolt_on_Circle.svg" alt="Icône énergie" width="72">
</div>

## Ton “carburant” de dresseur
L’énergie, c’est la jauge qui t’accompagne à chaque moment “action” sur PokeIsland. Quand tu utilises certains objets (notamment les **Poké Balls** pour capturer), tu consommes de l’énergie. Pas d’énergie = pas de capture (désolé, le Pokémon ne va pas attendre ton café).

## Les règles de base
- **Énergie max** : `100` par défaut (`default-max: 100`)
- **Recharge automatique** : **+1 énergie par minute** (`regen-per-minute: 1`)
- **Recharge hors-ligne** : oui, tu continues à en gagner même quand tu n’es pas connecté (`offline-regen-enabled: true`)
- **Bonus avec le niveau** : ton maximum d’énergie augmente avec ton niveau (`per-level-max-bonus: 1`)

Quand tu **passes au niveau supérieur**, ton énergie est restaurée à **100** (`level-up-restore: 100`).

## Combien coûte une Poké Ball ?
Chaque Poké Ball consomme un certain montant d’énergie (configurée côté serveur). Voici les valeurs principales :

| Poké Ball | Coût énergie |
|---|---:|
| `cobblemon:poke_ball` | 2 |
| `cobblemon:great_ball` | 3 |
| `cobblemon:ultra_ball` | 5 |
| `cobblemon:safari_ball` | 3 |
| `cobblemon:heavy_ball` | 4 |
| `cobblemon:master_ball` | 50 |

## Récupérer de l’énergie (les packs)
Tu peux recharger ton énergie avec des **packs** (consommables). D’après la config, ils restaurent :
- `pokeisland:small_energy_pack` : **+20**
- `pokeisland:energy_pack` : **+50**
- `pokeisland:large_energy_pack` : **+80**

## Messages utiles (si tu veux comprendre “pourquoi ça marche pas”)
- Si ton énergie est déjà au maximum : `Votre énergie est déjà au maximum.`
- Quand tu récupères un pack : `Vous avez récupéré +%amount% énergie.`
- Si tu n’en as pas assez : `Vous n'avez pas assez d'énergie (%current%/%max%)`
