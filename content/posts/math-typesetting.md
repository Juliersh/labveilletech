---
author: Julie Resch
title: Le social commerce fait marche arrière ...
date: 2023-01-25
description: Parlons un peu du social commerce et du social shopping dans notre société actuelle.
series: ["Themes Guide"]
---

<figure role="figure" aria-label="L'équipe du super daily">
   <img src="https://f.hellowork.com/blogdumoderateur/2019/01/super-daily-664x332.png"/>
   <figcaption>
      L'équipe du "super daily"
   </figcaption>
</figure>

Le **«  super daily »** c’est un podcast qui décrypte l’actualité des médias digitaux dans des petits épisodes qui analysent un thème ou une tendance en particulier. Dans ce podcast il était question de l’émergence du social commerce qui pourrait faire évoluer le social shopping. Petit point information : 

* Le social shopping : c’est le fait de passer du temps sur les réseaux sociaux, de se laisser inspirer, regarder les produits que les gens ont, et songer à se les procurer. 
* Le social commerce : c’est un peu ce qui manque au social shopping car une fois qu’on s’est inspiré et qu’on a repéré des produits on veut aller à l’étape finale : L’ACTE D’ACHAT. 

Et cet acte d’achat doit actuellement se faire sur une plateforme que détient la marque (site web, application, boutique physique…). Le social commerce pourrait révolutionner les achats online car il viserait à intégrer dans les réseaux sociaux directement l’achat d’un produit. Actuellement on peut par exemple sur Instagram les fonctionnalités de «  boutique » sur le profil et cliquer sur un produit pour être redirigé sur le site de la marque. Pouvoir réaliser l’achat directement sur Instagram permettrait de réduire considérablement le parcours d’achat et probablement augmenter le taux de conversion des utilisateurs. Et ça fait quelque temps que la toile s’agite autour de l’arrivée imminente de ce social commerce, d’autant plus qu’en Asie ça fait quelques années déjà que c’est en vogue et que ça rapporte des milliards : 

> «  Sur la version chinoise de TikTok (Douyin), le commerce in-stream est devenu sa plus grande source de revenus. »

> « EN Chine, les revenus des achats en direct dans les applications sociales ont dépassé les 400 milliards de dollars de CA. »

Et contre toute attente il semblerait que ça ne soit pas tout de suite pour nous; Européens et pour les Américains, car notamment le groupe Meta semble faire marche arrière sur la mise en place de ce social shopping.

> « Meta abandonne le social commerceLes utilisateurs aux États-Unis et en Europe n’ont pas montré beaucoup d’intérêt pour l’achat sur les applications sociales. Meta a
choisi fin 2022 d’arrêter ses fonctionnalités de commerce en Live sur Facebook. Idem, Instagram abandonne son programme d’affiliation. Tout récemment, Instagram a décidé de retirer l’onglet boutique de la page d’accueil de son application »

> «  Tiktok fait aussi marche arrière sur le social commerce en Europe et aux Etats-UnisLe lancement de TikTok Shop en 2022 n'a pas réussi à attirer suffisamment de consommateurs sur les marchés occidentaux pour en faire un succès.La plateforme a fait machine arrière à la find l’année dernière. »

Il semblerait donc que l’émergence du social commerce chez nous ne soit pas pour tout de suite et que l’avenir nous dira s’il deviendra une tendance dans les prochaines années.

##

J’ai trouvé ce podcast très intéressant et vraiment pertinent pour mon domaine d’activité. Ce qui est super avec les podcasts c’est que ça permet de se renseigner à des moments où on ne peut pas forcément être trop concentré sur une seule chose. Ça me permet d’apprendre des choses et me tenir au courant quand je suis en voiture ou en train ou alors quand je cuisine. En plus, il y a souvent plusieurs personnes qui interagissent entre elles, donc on a souvent droit à de vrais débat et a beaucoup d’échanges d’idées. C’est vraiment enrichissant de voir les avis de chacun et leur vision des choses. Cette thématique du social commerce est d’autant plus intéressante qu’elle vise à réduire les étapes pour convertir les prospects. Comme c’est un des grands défis actuels, il est facile de comprendre que ce social commerce pourrait vraiment bouleverser les choses et réduirait considérablement les parcours d’achats. Pour les personnes qui travaillent dans le domaine des parcours utilisateurs, c’est important de s’intéresser à ce genre de questionnement. Il est assez évident que si un jour le social commerce émerge et que l’acte d’achat se passe sur les réseaux sociaux, les sites e-commerce auront une tout autre dimension. On peut même imaginer qu’ils viennent à disparaitre…

##

Pour me tenir au courant de l’évolution de cette thématique j’ai décidé de mettre une Google Alerte sur le terme de «  social commerce ». Et je me suis abonnée au podcast du super Daily car j’ai vu beaucoup d’autres épisodes qui pourraient m’intéresser. J’en ai d’ailleurs sélectionné quelques-uns pour mettre dans ma liste d’écoute et pouvoir facilement les retrouver. 


lien du podcast : https://open.spotify.com/episode/2ey73GNM5V9ee5qMyH5VGB
























Mathematical notation in a Hugo project can be enabled by using third party JavaScript libraries.
<!--more-->

In this example we will be using [KaTeX](https://katex.org/)

- Create a partial under `/layouts/partials/math.html`
- Within this partial reference the [Auto-render Extension](https://katex.org/docs/autorender.html) or host these scripts locally.
- Include the partial in your templates like so:  

```bash
{{ if or .Params.math .Site.Params.math }}
{{ partial "math.html" . }}
{{ end }}
```

- To enable KaTex globally set the parameter `math` to `true` in a project's configuration
- To enable KaTex on a per page basis include the parameter `math: true` in content files

**Note:** Use the online reference of [Supported TeX Functions](https://katex.org/docs/supported.html)

{{< math.inline >}}
{{ if or .Page.Params.math .Site.Params.math }}
<!-- KaTeX -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.11.1/dist/katex.min.css" integrity="sha384-zB1R0rpPzHqg7Kpt0Aljp8JPLqbXI3bhnPWROx27a9N0Ll6ZP/+DiW/UqRcLbRjq" crossorigin="anonymous">
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.11.1/dist/katex.min.js" integrity="sha384-y23I5Q6l+B6vatafAwxRu/0oK/79VlbSz7Q9aiSZUvyWYIYsd+qj+o24G5ZU2zJz" crossorigin="anonymous"></script>
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.11.1/dist/contrib/auto-render.min.js" integrity="sha384-kWPLUVMOks5AQFrykwIup5lo0m3iMkkHrD0uJ4H5cjeGihAutqP0yW0J6dpFiVkI" crossorigin="anonymous" onload="renderMathInElement(document.body);"></script>
{{ end }}
{{</ math.inline >}}

### Examples

{{< math.inline >}}
<p>
Inline math: \(\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…\)
</p>
{{</ math.inline >}}

Block math:
$$
 \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } } 
$$
