---
layout: default
title: Oddíly
permalink: /oddily/
---

|    | 13:40 |    15:00    |    16:00    |    17:00    |  19:00  |
|----|-------|-------------|-------------|-------------|---------|
| Po |       | [Tan]/[Vše] |             | [Běh]/[R+D] | [Žen]   |
| Út |       |             | [Flo]*      | [Flo]*      |         |
| St |       |             | [Zál]/[Tra] | [Zál]/[Tra] |         |
| Čt |       |             | [Flo]*      | [Flo]*      | [Zdr]** |
| Pá | [Míč] | [Tra]       |             |             |         |

[Tan]: {{site.data.oddil.tanec.dlouhe-url}} "Tanec"
[Vše]: {{site.data.oddil.vsestrannost.dlouhe-url}} "Všestrannost"
[Běh]: {{site.data.oddil.beh.dlouhe-url}} "Běh"
[R+D]: {{site.data.oddil.rd.dlouhe-url}} "Rodiče a děti"
[Žen]: {{site.data.oddil.zeny.dlouhe-url}} "Ženy"
[Zál]: {{site.data.oddil.zalesak.dlouhe-url}} "Zálesák"
[Tra]: {{site.data.oddil.trampoliny.dlouhe-url}} "Trampolíny"
[Flo]: {{site.data.oddil.florbal.dlouhe-url}} "Florbal"
[Zdr]: {{site.data.oddil.zdravotni.dlouhe-url}} "Zdravotní cvičení"
[Míč]: {{site.data.oddil.micovky.dlouhe-url}} "Míčové hry"

\* Florbal – 16:00 – 17:00 trénují mladší žáci, 17:00 – 18:00 starší žáci.  
\** Zdravotní cvičení – sraz je před ZŠ Šestajovice v&nbsp;18:50.

{% for oddil_hash in site.data.oddil %}{% assign oddil = oddil_hash[1] %}
* [{{oddil.nazev}} ({{oddil.vek}})]({{oddil.dlouhe-url}}){% endfor %}

Chtěli byste se stát členy některého z následujících oddílů?

* badatelský oddíl
* oddílu všestrannosti mužů
* sokoláček dramaťáček
* oddíl olympijského šplhu
* běžecký oddíl

[Kontaktujte nás!](/kontakt/){:.button}

---

# Informace pro členy

{% for oddil_hash in site.data.oddil %}{% assign oddil = oddil_hash[1] %}
* [{{oddil.nazev}}](/{{oddil.kratke-url}}/){% endfor %}