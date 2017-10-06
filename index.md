---
title: Bienvenue aux ateliers 
---

{{ page.title}} - {{ site.title }}

Share the love

5 et 6 octobre : deux jours de conférences à l’[IBM Client Center à Bois-Colombes](https://www.paris-web.fr/lieux/#conferences).

7 octobre : une journée d'ateliers à la [Web School Factory à Paris](https://www.paris-web.fr/lieux/#ateliers). 

## Actualités

{% for post in site.posts %}
<a href="{{ post.url }}">{{ post.url }} - {{ post.title }} - {{ post.date }}</a>
{% endfor %}
