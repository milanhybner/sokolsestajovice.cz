---
layout: default
title: V Sokole sport pro všechny
permalink: /
---

{% assign curDate = site.time | date: '%s' %}
{% for post in site.posts reversed limit: 5 %}
    {% assign postStartDate = post.date | date: '%s' %}
    {% if postStartDate >= curDate %}
## [{{ post.title }}]({{ relative }}{{ post.url }})
{{ post.excerpt | markdownify }}
    {% endif %}
{% endfor %}

---

{% assign curDate = site.time | date: '%s' %}
{% for post in site.posts limit: 4 %}
    {% assign postStartDate = post.date | date: '%s' %}
    {% if postStartDate < curDate %}
## [{{ post.title }}]({{ relative }}{{ post.url }})
{{ post.excerpt | markdownify }}
    {% endif %}
{% endfor %}

[Všechny články]({{ relative }}/archiv/){:.button .special}

[Členství a příspěvky]({{ site.baseurl }}/clenstvi/){:.button} 
[Oddíly a rozvrh]({{ site.baseurl }}/oddily/){:.button} 
[Kalendář]({{ site.baseurl }}/kalendar/){:.button}
[Fotogalerie](http://sokolsestajovice.rajce.idnes.cz){:.button} 
[O Sokole]({{ site.baseurl }}/o-sokole/){:.button} 
[Kontakt]({{ site.baseurl }}/kontakt/){:.button}


<section class="tiles" id="oddily">
  <article class="style1">
    <span class="image">
      <img src="images/pic01.jpg" alt="" />
    </span>
    <a href="{{ relative }}{{site.data.oddil.vsestrannost.dlouhe-url}}/">
      <h2>Všestrannost</h2>
      <div class="content">
        <p>Cvičení pohybové všestrannosti pro děti ve věku 6–12 let. Cvičení je zaměřeno na pohybové aktivity gymnastika, atletika, míčové hry, plavání.</p>
      </div>
    </a>
  </article>
  <article class="style3">
    <span class="image">
      <img src="images/pic03.jpg" alt="" />
    </span>
    <a href="{{ relative }}{{site.data.oddil.zalesak.dlouhe-url}}/">
      <h2>Zálesák</h2>
      <div class="content">
        <p>Oddíl Zálesák je zaměřen na pobyty v přírodě a zálesácké táboření. Děti (8–12 let) se učí základům přežití v lese, jako je hledání a úprava vody, stavění přístřešků, rozdělávání ohně a zajišťování potravy. Dále se věnujeme poskytování první pomoci, lanovým technikám, poznávání rostlin, zvířat, stromů.</p>
      </div>
    </a>
  </article>
  <article class="style5">
    <span class="image">
      <img src="images/pic17.jpg" alt="" />
    </span>
    <a href="{{ relative }}{{site.data.oddil.tanec.dlouhe-url}}/">
      <h2>Tanec</h2>
      <div class="content">
        <p>Oddíl je určen dětem ve věku 6–16 let, dívkám i chlapcům. Taneční průprava zaměřená na jevištní - pódiový individuální a skupinový výrazový tanec, různé taneční způsoby - swing, street dance, hip hop, latino dance a především jejich kombinace a především vvýrazové prvky Nového cirkusu - pozemní a vzdušná akrobacie.</p>
      </div>
    </a>
  </article>
  <article class="style5">
    <span class="image">
      <img src="images/pic05.jpg" alt="" />
    </span>
    <a href="{{ relative }}{{site.data.oddil.tanecky.dlouhe-url}}/">
      <h2>Tanečky a rytmika</h2>
      <div class="content">
        <p>Děti (3–8 let) zde probudí přirozený vztah k tanci a pohybu s hudbou, potlačí stydlivost a vyjádří své emoce s hudbou.</p>
      </div>
    </a>
  </article>
  <article class="style4">
    <span class="image">
      <img src="images/pic04.jpg" alt="" />
    </span>
    <a href="{{ relative }}{{site.data.oddil.trampoliny.dlouhe-url}}/">
      <h2>Trampolíny</h2>
      <div class="content">
        <p>Oddíl pro chlapce ve věku 5–10 let, jehož náplní je všeobecná pohybová příprava prostřednictvím převážně gymnastických cvičení a skoky na trampolíně.</p>
      </div>
    </a>
  </article>
  <article class="style6">
    <span class="image">
      <img src="images/pic06.jpg" alt="" />
    </span>
    <a href="{{ relative }}{{site.data.oddil.zeny.dlouhe-url}}/">
      <h2>Kondiční cvičení</h2>
      <div class="content">
        <p>Sportovně koncipovaný trénink pro ženy. Obsahuje všechny možné cvičební prvky, taneční, posilující, relaxační i aerobní - vše pro získání či zvýšení kondice! Určeno všem ženám i mladší věkové kategorie!</p>
      </div>
    </a>
  </article>
  <article class="style2">
    <span class="image">
      <img src="images/pic07.jpg" alt="" />
    </span>
    <a href="{{ relative }}{{site.data.oddil.florbal.dlouhe-url}}/">
      <h2>Florbal</h2>
      <div class="content">
        <p>Oddíl florbalu pro věkovou kategorii mladších žáků (1.–5. třída) a starších žáků (6.–9. třída).</p>
      </div>
    </a>
  </article>
  <article class="style4">
    <span class="image">
      <img src="images/pic16.jpg" alt="" />
    </span>
    <a href="{{ relative }}{{site.data.oddil.zdravotni.dlouhe-url}}/">
      <h2>Zdravotní cvičení</h2>
      <div class="content">
        <p></p>
      </div>
    </a>
  </article>
  <article class="style6">
    <span class="image">
      <img src="images/pic11.jpg" alt="" />
    </span>
    <a href="{{ relative }}{{site.data.oddil.rd.dlouhe-url}}">
      <h2>Rodiče a děti</h2>
      <div class="content">
        <p>Cvičení je určeno dvojicím dospělý a dítě. Cvičení s rodičem (prarodičem) je aktivitou zaměřenou na rozvoj pohybové všestrannosti dítěte, budování vztahu k pohybu a upevňování správných pohybových návyků. Cv. obsahují řadu prostných cvičení, míčových her, cvičení na nářadí a cvičení s tradičním i netradičním náčiním.</p>
      </div>
    </a>
  </article>
  <article class="style1">
    <span class="image">
      <img src="images/parkour.jpg" alt="" />
    </span>
    <a href="{{ relative }}{{site.data.oddil.parkour.dlouhe-url}}">
      <h2>Parkour</h2>
      <div class="content">
        <p>Pro dospívající i dospělé. Umění přesunu z jednoho bodu do druhého v jakémkoli prostředí. Trénink odvahy, disciplíny a soustředění. Rozvoj síly, obratnosti a pohyblivosti.</p>
      </div>
    </a>
  </article>
  <article class="style2">
    <span class="image">
      <img src="images/micovky.jpg" alt="" />
    </span>
    <a href="{{ relative }}{{site.data.oddil.micovky.dlouhe-url}}/">
      <h2>Míčové hry</h2>
      <div class="content">
        <p>práce s míčem<br />pravidla míčových her<br />všestranná průprava pro míčové hry</p>
      </div>
    </a>
  </article>
  <article class="style2">
    <span class="image">
      <img src="images/muzi.jpg" alt="" />
    </span>
    <a href="{{ relative }}{{site.data.oddil.muzi.dlouhe-url}}/">
      <h2>Muži</h2>
      <div class="content">
        <p>Cvičení mužů. Síla, rychlost, vytrvalost.</p>
      </div>
    </a>
  </article>
</section>

