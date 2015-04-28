---
layout: post
og: true
og-type: article
title: "Web de l'exposició Figura i retrat en el fons d'art de la Fundació Iluro" 
share: true
class: artwork
categories:
  - portfoli
work: 5
---

{% assign work_data = site.data.portfoli | where:"id", page.work %}
{% assign work = work_data | first %}
<figure>
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_16-9">
			<core-image sizing="cover" class="core-image-size" preload fade src="/images/{{ work.featured-img }}"></core-image>	
		</div>
	</div>
	<figcaption>
		<p>{% if work.external-url %}<a href="{{ work.external-url }}"><small><i class="fa fa-external-link"></i> <strong>{{ work.name }}</strong></small></a>{% else if %}<small><strong>{{ work.name }}</strong></small>{% endif %}</p>
	</figcaption>
</figure>

<!--more-->

L'exposició “La figura i el retrat en els fons d'art de la Fundació Iluro” es configura com una mostra de les obres més destacades del fons. La mostra ha estat curosament comissariada per <a href="http://ca.wikipedia.org/wiki/Arnau_Puig_i_Grau" rel="external" title="Arnau Puig i Grau - Viquipèdia, l'enciclopèdia lliure">Arnau Puig</a>, reconegut crític d’art i sociòleg i un dels membres fundadors de la històrica revista “Dau al Set”.