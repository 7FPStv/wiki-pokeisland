---
description: Retrouve ici toutes les informations pour nous aider à améliorer ce wiki.
icon: pen-to-square
---

# Contribuer

Le wiki de PokeIsland est **ouvert à tous les joueurs**. Si tu repères une erreur, une info manquante ou une page à améliorer, tu peux proposer une modification directement via GitHub. Chaque contribution compte !

{% hint style="info" icon="circle-info" %}
Le repository du wiki est disponible ici : [github.com/7FPStv/wiki-pokeisland](https://github.com/7FPStv/wiki-pokeisland)
{% endhint %}

***

## Méthode simple

Tu veux corriger une faute ou modifier un paragraphe sans installer quoi que ce soit ? C'est possible directement depuis ton navigateur sur le lien github ci-dessus.

{% stepper %}
{% step %}
**Ouvre la page à modifier**

Navigue jusqu'au fichier `.md` concerné sur le repository GitHub.
{% endstep %}

{% step %}
**Clique sur l'icône de modification**

En haut à droite du fichier, clique sur l'icône **crayon** ✏️ `Edit this file`.
{% endstep %}

{% step %}
#### **Effectue ta modification**

Modifie le contenu dans l'éditeur en ligne. Les fichiers sont en **Markdown,** c'est un format simple à apprendre.
{% endstep %}

{% step %}
#### **Propose tes changements**

En bas de page, renseigne un titre court décrivant ta modification, puis clique sur **Propose changes**. GitHub crée automatiquement un fork et une Pull Request en ton nom.
{% endstep %}
{% endstepper %}

{% hint style="success" icon="circle-info" %}
Cette méthode est idéale pour les **petites corrections** : fautes, liens cassés, informations inexactes.
{% endhint %}

***

## Méthode complète

Pour des contributions plus importantes (nouvelle page, restructuration), la méthode complète avec Git est recommandée.

{% hint style="success" %}
**Pré-requis**

* Un compte GitHub : [Créer un compte](https://github.com/join)
* Git installé sur ton ordinateur : [Télécharger Git](https://git-scm.com/downloads)
* Un éditeur de texte, de préférence [Visual Studio Code](https://code.visualstudio.com/)
{% endhint %}

### Configurer Git

Après l'installation, ouvre ton terminal et configure ton identité :

```bash
git config --global user.name "Ton Pseudo"
git config --global user.email "ton-email@exemple.com"
```

{% stepper %}
{% step %}
### Forker le repository

Rends-toi sur [github.com/7FPStv/wiki-pokeisland](https://github.com/7FPStv/wiki-pokeisland) et clique sur **Fork** en haut à droite. Cela crée une copie personnelle du wiki sur ton compte GitHub.
{% endstep %}

{% step %}
### Cloner ton fork

Copie l'URL de ton fork puis dans ton terminal :

```bash
git clone https://github.com/TON-PSEUDO-GITHUB/wiki-pokeisland.git
cd wiki-pokeisland
```
{% endstep %}

{% step %}
### Créer une branche

Crée une branche dédiée à ta modification. Utilise un nom explicite :

```bash
git checkout -b ajout-guide-arenes
```
{% endstep %}

{% step %}
### Modifier le wiki



Ouvre le dossier dans Visual Studio Code et édite les fichiers `.md` concernés. Tu peux aussi créer de nouveaux fichiers si tu ajoutes une nouvelle page.

Structure Markdown de base à respecter :

```markdown
---
icon: nom-icone
description: Courte description de la page.
---

# Titre de la page

Introduction...

## Section

Contenu de la section.
```

{% hint style="warning" icon="circle-info" %}
Utilise la prévisualisation Markdown de VS Code avec **Ctrl + Shift + V** pour vérifier le rendu avant d'envoyer.
{% endhint %}
{% endstep %}

{% step %}
### Valider tes modifications

```bash
git add .
git commit -m "Ajout du guide sur les arènes"
```
{% endstep %}

{% step %}
### Envoyer sur GitHub

```bash
git push origin ajout-guide-arenes
```
{% endstep %}

{% step %}
### Ouvrir une Pull Request

* Retourne sur ton fork sur GitHub.
* Clique sur **Compare & pull request**.
* Décris clairement ce que tu as modifié et pourquoi.
* Clique sur **Create pull request**.

Un membre de l'équipe examinera ta proposition et l'intégrera si elle est validée.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
## Bonnes pratiques

* Reste clair et concis dans tes explications.
* Vérifie l'orthographe et la grammaire avant de soumettre.
* Respecte la structure et le style des pages existantes.
* Une contribution = une branche. Ne mélange pas plusieurs sujets dans une même PR.
* N'ajoute pas d'informations non vérifiées sur le gameplay
{% endhint %}

***

## Signaler un problème

Tu as repéré une erreur mais tu ne sais pas comment la corriger toi-même ? Ouvre une **Issue** sur GitHub en décrivant le problème :

[👉 Ouvrir une Issue](https://github.com/7FPStv/wiki-pokeisland/issues)
