---
layout: default
---
<div id="inimesed">
{% for inimene in site.inimesed %}
<div class="inimene">
	<h1><span class="kood">{{ inimene.kood }}</span> {{inimene.nimi}}</h1>
	<p>{{ inimene.amet }}</p>
	<p><img src="pildid/{{ inimene.nimi }}.jpg" alt="{{inimene.nimi}}"></p>
</div>
{% endfor %}
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/vanilla-lazyload/8.1.0/lazyload.min.js"></script>
<script>
	new LazyLoad();
</script>
