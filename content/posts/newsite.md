---
date: 2021-01-01
lastmod: 2021-01-01

weight: 2
title: "Création du site"
draft: false
author: "Da2ny"
description: "Découvrez comment créer son premier site avec hugo."

tags: ["Epitech", "Initialisation", "Hugo", "Github", "LoveIt"]
categories: ["documentation"]

lightgallery: true

toc:
  auto: false
---

Découvrez comment créer son premier site avec hugo.

<!--more-->


{{< admonition warning "Avertissement" true >}}
Les push se font sur origin master !
{{< /admonition >}}

## Initialisation (Help)

Quatre commandes seront nécessaires dans ce workshop:

Créer son projet Hugo:
```
hugo new site [RepoName]
```

Paramétrer son environement:
```
export HUGO_ENV="production hugo --gc --minify"
```

Générer un rendu de mise en production:
```
hugo --gc --minify
```

Générer un rendu local:
```
hugo server -D
```

## Création de son premier site statique

**Exercice: Créez votre premier sites avec les commandes ci-dessus**

{{< admonition tip "TIPS" false >}}
La dernière commande doit être la “Génération en un rendu de mise en production” car il va falloir l’héberger grâce à github.
{{< /admonition >}}

## Sauvegarde de votre projet

Créez vous un repo github basique où vous pousserez tout votre projet.

**Détail pour ajouter un repo git:**

(***à la racine de votre repo***)
```
git init .  && git remote add [le lien donné lorsque tu créer ton repo sur github] && git add . && git commit -m “[TON MESSAGE]" && git push origin master
```

## Hébergement du site

* Créez un nouveau repository sur github avec comme format de nom githubname.github.io

{{< admonition warning "ATTENTION" true >}}
Certains templates acceptent un format différent de **githubname.github.io** mais pour LoveIt c'est uniquement ce format.

Vous avez sinon la possibilité d'acheter un nom de domaine et créer plusieurs sites avec le nom de domaine.
{{< /admonition >}}

* **Dans ton repo public généré à la suite de la commande hugo --gc --minify**: tu vas pouvoir initialiser ton repo avec les commandes:
```
git init .  && git remote add [le lien donné lorsque tu créer ton repo sur github] && git add . && git commit -m “[TON MESSAGE]" && git push origin master
```

* Actualises ta page github et vas dans les settings de ton repo et fais comme montré ci-dessous

![image](/images/init/gif/github_masterbranch.gif)

**Clique sur la master branch**

Maintenant tu as un lien vers ton site. Retourne sur ton projet, ouvre ton fichier config.toml et place le lien à la place de la baseURL.
exemple: baseURL = "https://Da2ny.github.io"

Regénère ton projet pour une mise en production et push sur github. Attend quelques seconde et hardrefresh ton site et normalement tu verras une page blanche, ca veut dire que tu as réussis !

## LoveIt Template
Dans le repo themes tu vas pouvoir git clone le thème LoveIt (la commande que je t'avais demandé de copier et garder dans un coin).

* Vas dans le thème que tu as clone, example site, et tu copies le config.toml et tu remplace celui à la racine de ton repo par celui que tu as copié.

Relance ton site en local et regardes les modifications. Une erreur ? C’est normal tu n’as pas fais la configuration de base (base url / themes / etc). Lis le Bonus et passe au prochain topic.

## Bonus (Comment choisir un bon thème)

Un bon thème est assez complexe a trouver. Il faut absolument regarder :

* Dernière mise à jour

* Documentation complète

* Qualité du thème

* Réponses des créateurs aux questions

* Bugs