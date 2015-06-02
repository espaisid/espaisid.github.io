---
layout: post
og: true
og-type: article
title: "Fab Labs, nous mitjans i la generació de codi obert" 
share: true
class: artwork
categories:
  - capsulessid
capsula: 1
---

{% assign capsula_data = site.data.activitats.capsules | where:"id", page.capsula %}
{% assign capsula = capsula_data | first %}
<figure>
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_{{ capsula.aspect-ratio }}">
			<iron-image sizing="cover" class="iron-image-size" preload fade src="/images/capsules/{{ capsula.featured-img }}"></iron-image>	
		</div>
	</div>
	<figcaption>
		<p>{% if capsula.external-url %}<a href="{{ capsula.external-url }}"><small><i class="fa fa-external-link"></i> <strong>{{ capsula.name }}</strong></small></a>{% else if %}<small><strong>{{ capsula.name }}</strong></small>{% endif %}</p>
	</figcaption>
</figure>

<!--more-->

"Fab Labs, nous mitjans i la generació de codi obert", a càrrec d'Anastasia Pistofidou.

Dates: dissabte 16 de maig de 2015

"Fab Labs, nous mitjans i la generació de codi obert" consistí d’una introducció a l’escaneig i impressió 3D i les seves aplicacions en la producció i en la creació artística. Es va aprendre com funciona la tecnologia d’impressió 3D, els diferents projectes i màquines que existeixen i quina d’elles és la més adequada per a cada projecte.

---
<div class="row">
	<div class="col-md-offset-1 col-lg-offset-1 col-lg-5 col-md-5">
		<p><img src="/images/capsules/{{ capsula.images | first }}"></p>
	</div>
	<div class="col-lg-5 col-md-5">
		<p><img src="/images/capsules/{{ capsula.images | last }}"></p>
	</div>
</div>

##Informació addicional

**Anastasia Pistofidou**, Advanced Manufacturing Officer de Fab Lab Barcelona.
Anastasia Pistofidou és una arquitecta grega que treballa al Fab Lab Barcelona/IAAC com a cap de Advanced Manufacturing Office, especialitzada en desenvolupament de hardware, rapid prototyping i disseny de producció. Llicenciada en arquitectura per la Aristotle University de Tessalònica i amb un Màster (Fabbots 2011) per IAAC, treballa al Fab Lab Barcelona aplicant la fabricació digital a projectes de productes de disseny, arquitectura, mobiliari, instal·lacions, capsulasicions i creacions artístiques. Ha desenvolupat una personal línia de reserca, el Fab Textiles, sobre teixits, arquitectures “toves” i materials innovadors. Experimentant amb nous materials i processos de creació, combinant les tècniques de fabricació digitals amb les tradicionals, el seu treball és la demostració de com les noves tecnologies poden ajudar a canviar el consum massiu de moda a un de personal i local personalitzat en l’educació i la vida quotidiana. Anastasia també forma part de FirstV1sion, com a responsable d’innovació, desenvolupament per a samarretes d’esport que integren càmeres amb un sistema de transmissió HD. Així mateix, forma part d’un col·lectiu multidisciplinari (chinos International.cc), un grup artístic actiu de
programadors, dissenyadors interectius i artistes, fent-se càrrec de la part tangible d’instal·lacions i hardware.

Fab Lab Barcelona, és un dels principals laboratoris de la xarxa mundial de Fab Labs, un taller de producció i innovació a petita escala equipat amb eines de fabricació digital i tecnologies per a la producció d’objectes, prototips i electrònica.  Fab Lab Barcelona forma part de l’Institut d’Arquitectura Avançada
de Catalunya, donant recolzament als diferents programes educatius i d’investigació relacionats amb les múltiples escales de l’hàbitat humà. És també la seu de coordinació del programa internacional Fab Academy, una plataforma distribuïda de l’educació en el que cada lloc és una aula i el campus és el planeta, on els estudiants aprenen sobre els principis, les aplicacions i les implicacions de la tecnologia de fabricació digital.
[http://www.fablabbcn.org](http://www.fablabbcn.org)