---
title: Intelligence artificielle et art génératif
layout: default
---

# Ai-generative-Art
*Liste d'outils et de références pour la génération d'images et de vidéos par Intelligence Artificielle*

## Quelques outils
+ Article de fond sur le [Prompt Engineering](https://matthewmcateer.me/blog/clip-prompt-engineering/)
Le prompt engineering, c'est l'art de dialoguer avec l'IA pour lui faire générer des images de qualité.

+ Prompt Parrot
[Prompt Parrot](https://colab.research.google.com/drive/1ZZWvzsqjEHNn1qevQ4ed7Ozs4vij7qfc) est une IA qui assiste l'ingénieur Prompt dans la création d'expressions pertinentes et qualitatives pour l'IA. 

+ [Liste de livres](https://github.com/dvschultz/ml-art-colabs) Google Colab dédié à la génération d'images par IA.

## Ressources informatives
+ Le site web [Pharmapsychotic](https://pharmapsychotic.com/tools.html) recense des outils et des ressources en anglais.

+ Un [Lexique des termes cinematographiques](http://www.cinemaparlant.com/fichesactivites/ft_lexiquefrancaisanglais.pdf) en français et leur correspondance en anglais. En transmettant des notions de plans et de cadrage, on influence la prise de vue générée par la caméra virtuelle de l'IA.


## Dans le blog

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>