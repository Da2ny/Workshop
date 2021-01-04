---
date: 2021-01-01
lastmod: 2021-01-01

weight: 3
title: "Paramétrage du site"
draft: false
author: "Da2ny"
description: "Découvrez comment créer son premier site avec hugo."

tags: ["Epitech", "Paramétrage", "LoveIt"]
categories: ["documentation"]

lightgallery: true

toc:
  auto: false
---

Paramétrage du site.

<!--more-->

{{< admonition warning "Avertissement" true >}}
La création de plusieurs sites statiques avec un même Template peut générer des bugs (dir images non trouvé, pages about, tags, etc, mal redirrigés).

Pour faire plusieurs sites statiques il faut soit créer un nouveau compte github soit acheter un nom de domaine.
{{< /admonition >}}

## Exercice n°1

Configures ton .toml pour que ta page d’acceuil soit atractive. Enlève ou rajoute en fonction de ce que tu souhaite voir sur ton site.
{{< admonition danger "Danger" true >}}
Certains éléments sont plus important que d’autres lis bien ton .toml
{{< /admonition >}}

Si tu as oublié certains éléments tu pourras y revenir dans la dernière partie d’approfondissement.

{{< admonition note "Important à cofigurer" true >}}
baseURL = https://[GITHUB NAME].github.io/
themesDir = "./themes/"
{{< /admonition >}}

Si tu souhaite avoir ton site uniquement en français ou en anglais ou ... supprime la partie que tu ne veux pas ou rajoute une partie pour un autre langage.
La configuration est longue mais importante passe du temps dessus !

## Exercice n°2

Configure ton About, cela montre que tu es appliqué. Cela fait bonne impression.
Si tu souhaites avoir un logo utilises ce site pour transformer ton logo en paquet [favicon](https://realfavicongenerator.net).

Tu pourras unizip le paquet et le mettre dans ton dossier static et placer ton icon.(jpg/png) dans le dossier static/images/ (Ces informations peuvent être trouvées dans le config.toml et en regardant les fichiers mis dans themes/LoveIt/exampleSite).