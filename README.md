---
layout: page
title: "Intelligence artificielle et art génératif"
permalink: https://fredericpierron.github.io/index.html
---

# Ai-generative-Art
*List of tools and ressources for generative and ai art*

(Prompt Engineering https://matthewmcateer.me/blog/clip-prompt-engineering/()

Prompt Parrot
https://colab.research.google.com/drive/1ZZWvzsqjEHNn1qevQ4ed7Ozs4vij7qfc?usp=sharing

ML Art Colabs books available
https://github.com/dvschultz/ml-art-colabs

Tools and Ressources for AI Art
https://pharmapsychotic.com/tools.html

Lexique des termes cinematographiques (FR/ENG)
http://www.cinemaparlant.com/fichesactivites/ft_lexiquefrancaisanglais.pdf


## In the blog

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>