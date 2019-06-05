---
layout: default
title: V Sokole sport pro všechny
permalink: /
---

![Tour de Club plakát]({{ relative }}/images/2019-tour-de-club.jpg "Tour de Club plakát"){:.image .fit}

<div class="row">
  <div class="12u$(medium)">
    <p><a href="{{ site.baseurl }}/clenstvi/" class="button">Členství</a>
    <a href="{{ site.baseurl }}/oddily/" class="button">Oddíly a rozvrh</a>
    <a href="{{ site.baseurl }}/kalendar/" class="button">Kalendář akcí</a>
    <a href="http://sokolsestajovice.rajce.idnes.cz" class="button">Fotogalerie</a>
    <a href="{{ site.baseurl }}/o-sokole/" class="button">O Sokole</a>
    <a href="{{ site.baseurl }}/kontakt/" class="button">Kontakt</a>
    </p>
  </div>
</div>


<div class="row">
  <div class="12u$(medium)">
    <p><iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Ftjsokolsestajovice%2F&tabs=timeline&height=400&small_header=true&adapt_container_width=true&hide_cover=true&show_facepile=false&appId=469260143436623" style="width:400px;height:400px;border:none;overflow:hidden;margin-bottom:20px" scrolling="no" frameborder="0" allowTransparency="true" ></iframe></p>
  </div>
</div>

{% assign curDate = site.time | date: '%s' %}
{% for post in site.posts reversed limit: 5 %}
    {% assign postStartDate = post.date | date: '%s' %}
    {% if postStartDate >= curDate %}
## [{{ post.title }}]({{ relative }}{{ post.url }})
{{ post.excerpt | markdownify }}
    {% endif %}
{% endfor %}

{% assign curDate = site.time | date: '%s' %}
{% for post in site.posts limit: 5 %}
    {% assign postStartDate = post.date | date: '%s' %}
    {% if postStartDate < curDate %}
## [{{ post.title }}]({{ relative }}{{ post.url }})
{{ post.excerpt | markdownify }}
    {% endif %}
{% endfor %}

<!--
![Zálesák nábor plakát]({{ relative }}/images/2018-zalesak-nabor.jpg "Zálesák nábor plakát"){:.image .fit}

[Zálesák – nábor – plakát (.pdf)]({{ relative }}/files/2018-zalesak-nabor.pdf){:.button .icon .fa-download}

![Florbal nábor plakát]({{ relative }}/images/2018-florbal-nabor.jpg "Florbal nábor plakát"){:.image .fit}
-->

[Všechny články]({{ relative }}/archiv/){:.button .special}
