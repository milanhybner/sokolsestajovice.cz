---
layout: default
title: V Sokole sport pro všechny
permalink: /
---

<div class="row">
  <div class="12u$(medium)">
    <p><a href="{{ site.baseurl }}/clenstvi/" class="button">Členství a příspěvky</a>
    <a href="{{ site.baseurl }}/oddily/" class="button">Oddíly a rozvrh</a>
    <a href="http://sokolsestajovice.rajce.idnes.cz" class="button">Fotogalerie</a>
    <a href="{{ site.baseurl }}/o-sokole/" class="button">O Sokole</a>
    <a href="{{ site.baseurl }}/kontakt/" class="button">Kontakt</a>
    </p>
  </div>
</div>
<div class="row">
  <div class="12u$(medium)">
    <iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Ftjsokolsestajovice%2F&tabs=timeline&width=1000&height=500&small_header=true&adapt_container_width=true&hide_cover=true&show_facepile=false&appId=469260143436623" style="width:800px;height:400px;border:none;overflow:hidden;margin-bottom:20px" scrolling="no" frameborder="0" allowTransparency="true" ></iframe>
  </div>
</div>

# Chystáme

{% assign curDate = site.time | date: '%s' %}
{% for post in site.posts reversed limit: 5 %}
    {% assign postStartDate = post.date | date: '%s' %}
    {% if postStartDate >= curDate %}
## [{{ post.title }}]({{ relative }}{{ post.url }})
{{ post.excerpt | markdownify }}
    {% endif %}
{% endfor %}

<a href="{{ site.baseurl }}/kalendar/" class="button">Více info v kalendáři</a>

---

# Proběhlo

{% assign curDate = site.time | date: '%s' %}
{% for post in site.posts limit: 8 %}
    {% assign postStartDate = post.date | date: '%s' %}
    {% if postStartDate < curDate %}
## [{{ post.title }}]({{ relative }}{{ post.url }})
{{ post.excerpt | markdownify }}
    {% endif %}
{% endfor %}

[Všechny články]({{ relative }}/archiv/){:.button .special}



