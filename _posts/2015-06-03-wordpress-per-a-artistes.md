---
layout: post
og: true
og-type: article
title: "WordPress per a artistes" 
share: true
class: artwork
categories:
  - capsulessid
capsula: 2
---

{% assign capsula_data = site.data.activitats.capsules | where:"id", page.capsula %}
{% assign capsula = capsula_data | first %}
<figure>
	<a href="{{ page.url }}">
		<div class="padding-artwork-container">
			<div class="embed-container embed-container_{{ capsula.aspect-ratio }}">
				<iron-image sizing="cover" class="iron-image-size" preload fade src="/images/capsules/{{ capsula.featured-img }}"></iron-image>	
			</div>
		</div>
	</a>
	<figcaption>
		<p>{% if capsula.external-url %}<a href="{{ capsula.external-url }}"><small><i class="fa fa-external-link"></i> <strong>{{ capsula.name }}</strong></small></a>{% else if %}<small><strong>{{ capsula.name }}</strong></small>{% endif %}</p>
	</figcaption>
</figure>

<!--more-->
<br/>

"WordPress per a artistes", a càrrec de Ramon Gil.

Dates: dissabte 20 de juny de 2015

Taller pràctic sobre com crear un lloc web basat en la plataforma WordPress. El taller té 3 blocs: 

- Primer, breu introducció a Internet i la Web com plataforma de difusió de l'obra d'un artista. 
- Segon, "WordPress.com", com a solució gratuïta de tenir un web fàcil de crear i mantenir. 
- Tercer, la plataforma WordPress personalitzada: web amb domini propi, plantilla professional i gestió i manteniment de plugins.

Inscripcions: <a class ="btn btn-default" title="Inscriu-t'hi!" href="mailto:info@artinpocket.cat?subject=Inscripci%C3%B3%20a%20la%20C%C3%A0psulaSID%20WordPress%20per%20a%20artistes&body=Eps%2C%20que%20em%20vull%20inscriure%20a%20la%20C%C3%A0psulaSID%20WordPress%20per%20a%20artistes">info@artinpocket.cat</a>