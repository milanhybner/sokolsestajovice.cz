---
layout: default
title: Oddíly
permalink: /oddily/
---

# Oddíly

{% for oddil_hash in site.data.oddil %}{% assign oddil = oddil_hash[1] %}
* [{{oddil.nazev}} ({{oddil.vek}})]({{oddil.dlouhe-url}}){% endfor %}

Chtěli byste se stát členy některého z následujících oddílů?

* badatelský oddíl
* oddílu všestrannosti mužů
* sokoláček dramaťáček
* oddíl olympijského šplhu
* běžecký oddíl
* oddíl míčových her

[Kontaktujte nás!]({{ http://www.sokolsestajovice.cz }}/kontakt/){:.button}




