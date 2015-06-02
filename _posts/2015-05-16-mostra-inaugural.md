---
layout: post
og: true
og-type: article
title: "Mostra inaugural" 
share: true
class: artwork
categories:
  - exposicionssid
expo: 1
---

{% assign expo_data = site.data.activitats.exposicions | where:"id", page.expo %}
{% assign expo = expo_data | first %}
<figure>
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_{{ expo.aspect-ratio }}">
			<iron-image sizing="cover" class="iron-image-size" preload fade src="/images/exposicions/{{ expo.featured-img }}"></iron-image>	
		</div>
	</div>
	<figcaption>
		<p>{% if expo.external-url %}<a href="{{ expo.external-url }}"><small><i class="fa fa-external-link"></i> <strong>{{ expo.name }}</strong></small></a>{% else if %}<small><strong>{{ expo.name }}</strong></small>{% endif %}</p>
	</figcaption>
</figure>

<!--more-->

"Mostra inaugural", amb la participació artística de Maria Bartrons, Alba Danés, La Wäwä, Xevi Masmitjà, Roger Serrat-Calvó i Mònica Quintana.

Dates: dissabte 16 de maig de 2015

"Mostra inaugural" va ser una exposició eclèctica i, artísticament, multidisciplinar amb una selecció de sis artistes emergents. Cadascun d'ells va presentar els seus treballs més recents i significatius de les seves trajectòries artístiques. L'exposició anà acompanyada d'un minimercat d'art amb obres dels mateixos artistes.

---
<div class="row">
	<div class="col-md-offset-1 col-lg-offset-1 col-lg-5 col-md-5">
		<p><img src="/images/exposicions/{{ expo.images | first }}"></p>
	</div>
	<div class="col-lg-5 col-md-5">
		<p><img src="/images/exposicions/{{ expo.images | last }}"></p>
	</div>
</div>

##Informació addicional

**Maria Bartrons**. Llicenciada en Història de l'Art a la UAB al 2006, cursa posteriorment el Màster: Arquitectura, Art i Espai efímer amb especialització Espai expositiu i Escenografia de la UPC ; formació que més tard complementa amb un Stage Eurodysée de Construcció de decorats i vestuari a França durant el curs '11-'12. Compaginant sempre formació de dibuix i pintura junt amb diferents projectes teatrals i audiovisuals, aprofita per realitzar un curs a la Central Saint Martins de Londres, per endinsar-se de ple en el surrealista món del collage.

**Alba Danés**.  Llicenciada en Ciències de la Comunicació i Tècnica Superior en Fotografia Artística. [http://www.albadanes.com/](http://www.albadanes.com/)

L'objecte dels projectes d'Alba Danés és la relació entre l'entorn natural i l'individu social. Un intent de descobrir i documentar conscient i activament els paisatges i les persones que l'habiten. Un procés que sovint fa essencial la suma de paisatge i retrat amb els conseqüents vincles fotogràfics que s'estableixen entre ells. Caminar ha esdevingut una pràctica estètica, una metodologia sacrificada duta a terme amb actitud de resistència. Amb aquesta praxis en ment he proposat àlbums de residus paisatgístics, de franges a ciutats, d'espais per a una nova descoberta o per l'oblit etern, jocs de deambulació on individus i paisatges comparteixen protagonisme. Els retrats a persones i paisatges, així com les possibles descripcions són la voluntat de deixar constància del qui, el com i el perquè m'envolta. Una aproximació des de la imatge per qüestionar la relació entre paisatge, societat i individu, una revisió a la gestió d'espais i emocions del món contemporani.

**La Wäwa**. Des que tinc ús de raó que els llapis de colors i dibuixar forma part de la meva vida. Vaig començar a formar-me fent Belles Arts a Barcelona, aquí fou on em vaig donar compte allò que realment volia: era especialitzar-me en el món de la il·lustració. A partir d'aquí vaig realitzar el curs d'il·lustració a l'escola Francesca Bonnemaison de Barcelona i en la Joso. Durant els meus anys a Barcelona vaig fer diferents exposicions individuals i col·lectives en diferents centres i galeries. Entre elles, el Niu bcn o El Arco de la Virgen i aquí fou on van néixer les meves Wäwïs, nines que diuen que transmeten fragilitat, força, passió, por, bellesa… trossets de mi. Cada figura encarna un instant de la meva vida, un fragment d'experiència íntima que, a través de l'art, esdevé social. Actualment, fa tres anys que visc a Figueres on treballo com a il·lustradora freelance. La meva vida és dibuixar, gaudir de la naturalesa, llegir i buscar projectes interessants, reptes i evolucionar com a professional. M'encanta el cafè, riure, els meus amics i el silenci de la muntanya.

**Xevi Masmitjà**, estudià a la facultat de belles arts de Barcelona. Ha participat en diverses exposicions col·lectives i individuals. Està especialitzat en pintura, el seu treball és informalista i experimental. Per mitjà del moviment i l'acció crea trames de diferents tipus que se superposen creant efectes de realitat. És una abstracció calculada i matisada, amb la finalitat d'obtenir figuracions estranyes, que ens poden fer pensar en paisatges o objectes deslocalitzats. Al mateix temps, les seves composicions són dinàmiques, i procuren estar absentes de contingut superflu.

**Roger Serrat-Calvó**. Després de llicenciar-se en Belles Arts amb l'especialitat d'imatge per la Universitat de Barcelona (2004), va realitzar un curs d'especialització en imatge publicitària, editorial i de moda a IDEP. A l'estiu del 2005 va iniciar els seus estudis de doctorat a la Universitat de Barcelona, obtenint el certificat d'estudis avançats (DEA) al 2007. Des de fa alguns anys compagina l'activitat de fotògraf freelance amb la docència i el desenvolupament dels seus projectes fotogràfics. Des de llavors, ha exposat en espais com Kowasa Gallery de Barcelona, El Centre Cultural la Mercè de Girona o la Sala 15 d'Olot. També ha guanyat diversos premis i beques com Rodalies 4,la Beca-Olot fotografia de Paisatge o més recentment una beca Agita a Figueres. També És soci fundador i president de l'Associació Binari per la promoció de la cultura i l'art contemporanis. 

**Mònica Quintana**. Sóc una apassionada de qualsevol forma artística, llicenciada en Història de l'Art. A la fotografia, que practico des de finals de 2011, he trobat la meva veu. Intento crear fotografies amb ànima, que ens traslladin, ens inspirin, ens expliquin quelcom i ho facin de forma màgica, diferent i única. Sempre que treballo amb algú, sigui un adult, un nen, un jove, intento captar la seva essència mitjançant allò que li agrada, allò que el commou, allò que el representa. Em motiva fer fotografies diferents, crear records únics, i fer de la sessió fotogràfica una experiència especial. Crec en l'art com una forma de millorar les nostres vides. I crec que és possible que estigui a l'abast de tothom.