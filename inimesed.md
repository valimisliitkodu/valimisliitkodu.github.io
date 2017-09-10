---
layout: default
---

<div id="inimesed">
{% for inimene in site.inimesed %}
<div class="inimene">
	<h1><span class="kood">{{ inimene.kood }}</span> {{inimene.nimi}}</h1>
	<p>{{ inimene.amet }}</p>
	<p><img src="pildid/{{ inimene.nimi }}.jpg"></p>
</div>
{% endfor %}
</div>