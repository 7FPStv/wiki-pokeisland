---
description: >-
  Transforme un coffre de ton île en boutique : vends tes objets aux autres
  joueurs, ou rachète-leur ce dont tu as besoin.
icon: store
---

# Shops joueurs

Chaque joueur peut transformer un **coffre de son île** en **boutique** : les autres joueurs viennent y acheter tes objets, ou te revendre ceux que tu recherches, contre des PokéCoins. <kbd>**/ps**</kbd>

{% hint style="info" %}
Un shop ne se crée que **sur ta propre île**. Sans île, ou sur l'île d'un autre joueur, la création est refusée.
{% endhint %}

***

## Créer un shop

1. Va sur **ton île** et pose un **coffre** (coffre classique ou coffre piégé). Les tonneaux, shulkers, entonnoirs, fours et autres conteneurs ne sont pas acceptés.
2. Prends en main l'**objet à vendre**, **accroupis-toi** et fais un **clic gauche** sur le coffre.
3. Tape le **prix unitaire** dans le chat, entre **1** et **99 999 999** PokéCoins. Écris `cancel` pour annuler.
4. Un **panneau** apparaît sur le coffre, avec ton pseudo, le mode, le stock et le prix. L'objet vendu s'affiche au-dessus.

{% hint style="warning" %}
Le **stock**, c'est le contenu du coffre : pense à le **remplir** avec l'objet que tu vends. Un coffre vide ne vend rien.
{% endhint %}

Pour le moment, chaque joueur peut avoir **un seul shop**.

***

## Gérer ton shop

Fais un **clic droit sur le panneau** de ton shop pour ouvrir son menu :

| Action | Ce que ça fait |
| ------ | -------------- |
| **Changer de mode** | **Vente** : tu vends l'objet aux clients. **Achat** : tu rachètes l'objet aux clients avec ton propre argent. |
| **Changer le prix** | Nouveau prix unitaire, aussi possible avec `/ps price <prix>` |
| **Historique** | Les **10 dernières** transactions du shop |
| **Membres** | Ajoute ou retire des joueurs qui peuvent gérer le shop avec toi : `/ps staff add` ou `remove <joueur>` |
| **Fermer / ouvrir** | Ferme le shop **sans le supprimer** : les clients voient « Fermé » sur le panneau |
| **Supprimer** | Supprime le shop. Le **contenu du coffre est conservé**. |

{% hint style="info" %}
En mode **Achat**, il te faut **assez d'argent** pour payer les clients et **de la place** dans le coffre pour ranger ce qu'ils te vendent. Sinon, la transaction est annulée.
{% endhint %}

Tu reçois une **notification à chaque vente**.

***

## Acheter et vendre dans un shop

Fais un clic sur le **panneau** d'un shop : un menu s'ouvre pour choisir la **quantité** (boutons ±1, ±16, ±64, et « Max » en mode vente), puis valide.

* Tu ne peux pas commercer avec **ton propre shop**, ni avec un shop dont tu es **membre**.
* Si le stock du shop ou ton argent ne suffit pas, la transaction est annulée et rien n'est perdu.

### Trouver un objet

`/ps search <objet>` liste **tous les shops du serveur** qui proposent cet objet. Tu peux les trier par **prix** ou par **propriétaire**, et un clic te **téléporte** directement au shop.

{% hint style="success" %}
Avant d'acheter au [Marchand Shop](marchand-shop.md) ou sur le [GTS](gts.md), fais un `/ps search` : un autre joueur le vend peut-être moins cher.
{% endhint %}

***

## Commandes

`/ps` est le raccourci de `/playershops`.

| Commande | Effet |
| -------- | ----- |
| `/ps search <objet>` | Chercher un objet dans tous les shops |
| `/ps mode` | Passer ton shop en vente ou en achat |
| `/ps price <prix>` | Changer le prix de ton shop |
| `/ps staff [add\|remove] <joueur>` | Gérer les membres de ton shop |
| `/ps transactions` | Voir les dernières transactions |
| `/ps delete` | Supprimer ton shop |
