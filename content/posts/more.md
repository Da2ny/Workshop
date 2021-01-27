---
date: 2021-01-01
lastmod: 2021-01-01

weight: 6
title: "Approfondissement des connaissances"
draft: false
author: "Da2ny"
description: "Découvrez comment créer son premier site avec hugo."

tags: ["Epitech", "Approfondissement", "LoveIt", "googleAnalitics", "googlesearch", "gitalk"]
categories: ["documentation"]

lightgallery: true

toc:
  auto: false
---

Approfondissement des connaissances.

<!--more-->

## Sortez vos lunettes

Dans cette partie je vais te montrer tous les éléments importants a remplir dans ton .toml !

Aller c’est parti, ouvre ton .toml et regarde et rempli chaque éléments que je vais te dire !

La liste est dans l’ordre !

{{< admonition note "Partie 1" true >}}
baseURL

defaultContentLanguage

theme

themesDir

title (c’est pour le titre de l’onglet)
{{< /admonition >}}

Ceux la étaient basiques ! On continue !

{{< admonition note "Partie 2" true >}}
La partie des about / tags / categories regarde bien à quoi servent chacun d’entre eux !

paginate

googleAnalytics (c’est pour plus tard :D)

description (important lorsque tu envoi ton site sur des résaux sociaux !)

keywords (choisis de bon tags pour que ton site soit le mieux répertorié possible ! (tu veras ça avec les google search))

title

noFavicon (tu veux voir ton icon sur la page de l’onglet ? laisse le en false)

tileColor

avatarURL

title && subtitle

[languages.fr/en.params.social]
{{< /admonition >}}


Il y en a un bon paquet !

{{< admonition note "Partie 3" true >}}
defaultTheme

dateFormat

images

name
{{< /admonition >}}

Je te fais un petit cadeau en te donnant un joli footer ! Renseigne toi il y a une histoire dèrière ce footer.
```
# Footer config
  [params.footer]
    enable = true
    # Custom content (HTML format is supported)
    custom = '<a title="http://kopimi.com" href="http://kopimi.com" target="_blank"><img src="https://kopimi.com/kopimi/k/kopimi_dialektik.gif" style="width:100px;height:50px;"></a>'
    # whether to show Hugo and theme info
    hugo = false
    # whether to show copyright info
    copyright = false
    # whether to show the author
    author = false
    # site creation time
    since = 2019
    # ICP info only in China (HTML format is supported)
    icp = ""
    # license info (HTML format is supported)
    license= ""
```

Et la suite …

{{< admonition note "Partie 4" true >}}
[params.page.share]
```
params.page.comment.gitalk]
enable = false
owner = ""
repo = ""
clientId = ""
clientSecret = ""
```

(On verra ça plus tard aussi !)

name

logoUrl = “/images/avatar.png”

[author]

name

email

link
{{< /admonition >}}

Maintenant que tu as vu tout ça tu vas pouvoir passer aux 3 exercices suivant !

## Exercice n°1

* Créer toi un compte google analytics et mets le code secret dans le config.toml

## Exercice n°2

* Créer toi un compte google search et mets le code secret dans le config.toml

**Le code doit être placé dans la variable google**

{{< admonition tip "TIPS" false >}}
[params.verification]

google = ""

bing = ""

yandex = ""

pinterest = ""

baidu = ""
{{< /admonition >}}

## Exercice n°3

* Installe gitalk et je te laisse remplir la catégorie gitalk du config.toml tout seul.

## Exercice final
Non je rigole c’est déjà finit, amuse toi bien avec les compétences que tu as aquis et découvre aussi plein de nouveaux templates !

Voici un example de site avec un autre template -> [SiteExemple](https://sharkigamers.github.io/escape.gitgub.io/fr/)