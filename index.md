---
title: Bienvenue aux ateliers 
---

{{ page.title}} - {{ site.title }}

Share the love

5 et 6 octobre : deux jours de conférences à l’[IBM Client Center à Bois-Colombes](https://www.paris-web.fr/lieux/#conferences).

7 octobre : une journée d'ateliers à la [Web School Factory à Paris](https://www.paris-web.fr/lieux/#ateliers). 

## Actualités

{% for post in site.posts %}
<a href="{{ site.baseurl }}{{ post.url }}">{{ site.baseurl }}{{ post.url }} - {{ post.title }} - {{ post.date }}</a>
{% endfor %}

## Boucle sur des fichiers

{% for image in site.static_files limit: 3 %}
  {{ image.name }} - {{ image.modified_time }}<br>
{% endfor %}

## Boucle sur une collection

{% raw %}
```
// Exemple de boucle
{% for collection in site.themes %}
  {{ collection.title }}
  {{ collection.url }} 
{% endfor %}
```
{% endraw %}

{% for collection in site.collections %}
<a href="{{ collection.url }}">{{ collection.url }}</a>
	{{ collection.title }}
	{{ collection.date }}
{% endfor %}
