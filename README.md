# Ai-generative-Art
*List of tools and ressources for generative and ai art*

Prompt Engineering
https://matthewmcateer.me/blog/clip-prompt-engineering/

Prompt Parrot
https://colab.research.google.com/drive/1ZZWvzsqjEHNn1qevQ4ed7Ozs4vij7qfc?usp=sharing

ML Art Colabs books available
https://github.com/dvschultz/ml-art-colabs

Tools and Ressources for AI Art
https://pharmapsychotic.com/tools.html

Lexique des termes cinematographiques (FR/ENG)
http://www.cinemaparlant.com/fichesactivites/ft_lexiquefrancaisanglais.pdf


{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}



{% if page.show_sidebar %}
  <div class="sidebar">
    sidebar content
  </div>
{% endif %}