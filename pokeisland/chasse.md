---
icon: bullseye-arrow
---

# Chasse

<div align="center">
  <img src="https://commons.wikimedia.org/wiki/Special:FilePath/Paw-print.svg" alt="Icône piste" width="72">
</div>

## Chasser des Pokémon (et gagner des récompenses)
La **Chasse** te permet de tenter ta chance en mode “détective Pokémon”. Tu lances une session, et au fil du temps tu peux capturer/tenter une chasse selon la mécanique du serveur.

## Ouvrir la Chasse
Tu peux ouvrir l’interface avec :
- la commande : `/chasse`

Une fois l’interface ouverte, tu suis simplement les options proposées à l’écran.

## Durée & cadence
Les paramètres côté serveur sont :
- **Durée** : `60` minutes
- **Chasses individuelles** : activé (`individualHunts: true`)
- Le système gère les contrôles et timers avec un petit buffer technique (`bufferDuration: 5`)

## Raretés (les probabilités)
Chaque chasse est associée à une rareté :
| Rareté | Chance |
|---|---:|
| Commun | 60% |
| Peu commun | 30% |
| Rare | 9% |
| Ultra rare | 1% |

## Les récompenses
Tu reçois des récompenses basées sur la rareté (économie + jetons). Le serveur annonce aussi le début/fin de chasse via des messages dans le chat.

Exemples de récompenses par rareté (valeurs configurées) :
- **Commun** : `eco +100` + `1` jeton
- **Peu commun** : `eco +500` + `2` jetons
- **Rare** : `eco +700` + `3` jetons
- **Ultra rare** : `eco +1000` + `4` jetons

Il existe également des **prix personnalisés** pour certaines espèces (ex : `magikarp` peut donner un `minecraft:diamond 1` dans la config).

## Conseils “joueur”
- Si tu es juste en énergie, recharge avant : tout le monde préfère “chasser”, pas “regarder son inventaire en panique”.
- Les ultra rares ne se forcent pas : l’important, c’est de chasser régulièrement.
