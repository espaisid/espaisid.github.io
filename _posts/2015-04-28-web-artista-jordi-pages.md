---
layout: post
og: true
og-type: article
title: "Web de l'artista Jordi Pagès" 
share: true
class: artwork
categories:
  - portfoli
work: 6
---

{% assign work_data = site.data.portfoli | where:"id", page.work %}
{% assign work = work_data | first %}
<figure>
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_16-9">
			<iron-image sizing="cover" class="iron-image-size" preload fade src="/images/{{ work.featured-img }}"></iron-image>	
		</div>
	</div>
	<figcaption>
		<p>{% if work.external-url %}<a href="{{ work.external-url }}"><small><i class="fa fa-external-link"></i> <strong>{{ work.name }}</strong></small></a>{% else if %}<small><strong>{{ work.name }}</strong></small>{% endif %}</p>
	</figcaption>
</figure>

<!--more-->

Web l'artista Jordi Pagès (1951) és un artista de Granollers molt vinculat a Cadaqués, on també hi té estudi, amb una llarga trajectòria artística. Lector apassionat, en especial de la poesia, l’utilitza com a diàleg creatiu amb conseqüències quasi sempre imprevisibles. Optant per tenir més llibertat, ha presentat la seva obra en galeries, llibreries, espais singulars,etc.... Les seves obres són una síntesi d’esferes imaginables, començant per la poesia o la pintura, passant per la música o el cinema, i finalitzant amb un calidoscopi artístic. És per aquest fet que Jordi Pagès utilitza sobretot el collage, per donar cabuda a tot el seu eclèctic imaginari creatiu.