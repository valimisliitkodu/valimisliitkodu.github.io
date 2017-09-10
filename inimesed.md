---
layout: default
---

{% for inimene in site.inimesed %}
<h1>{{ inimene.kood }} {{inimene.nimi}}</h1>
<p>{{ inimene.amet }}</p>
<img src="pildid/{{ inimene.pilt }}">
{% endfor %}