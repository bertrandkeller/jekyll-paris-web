---
title: Bienvenue aux ateliers 
---

{{ page.title}} - {{ site.title }}

Share the love

5 et 6 octobre : deux jours de conférences à l’[IBM Client Center à Bois-Colombes](https://www.paris-web.fr/lieux/#conferences).

7 octobre : une journée d'ateliers à la [Web School Factory à Paris](https://www.paris-web.fr/lieux/#ateliers). 

## Actualité

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }})
{% endif %}

<ul>
{% for post in site.posts %}
<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endif %}
</ul>
