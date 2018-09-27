---
layout: default
title: Inimesed
---
<div id="inimesed">
{% for inimene in site.inimesed %}
<div class="inimene">
	<h1><span class="kood">{{ inimene.kood }}</span> {{inimene.nimi}}</h1>
	<p>{{ inimene.amet }}</p>
	{% if inimene.tegevus %}
	<p>{{ inimene.tegevus}}</p>
	{% endif %}
	<p><img src="pildid/{{ inimene.nimi }}.jpg" alt="{{inimene.nimi}}"></p>
</div>
{% endfor %}
</div>
