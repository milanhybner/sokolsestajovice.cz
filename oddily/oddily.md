---
layout: default
title: Oddíly
permalink: /oddily/
---

## Rozvrh

Uvedený čas značí začátek lekcí. Pro podrobnější informace klikněte na příslušný oddíl.

|    | 10:15 | 14:00 |      15:00       | 16:00 |      17:00       |      19:00       |
|----|-------|-------|------------------|-------|------------------|------------------|
| Po | [ZDP] |       | [TAN]<br />[VŠE] |       | [RaD]            | [ŽEN]<br />[MUŽ] |
| Út |       |       |                  | [TR1] | [TR2]            |                  |
| St |       |       |                  | [ZÁL] | [ZÁL]<br />[TaR] |                  |
| Čt |       |       |                  | [FL1] | [FL2]            | [ZDR]*           |
| Pá |       |       | [MÍČ]            |       |                  |                  |
| So |       | [FL1] | [FL2]            |       |                  |                  |

[TAN]: http://www.sokolsestajovice.cz/{{site.data.oddil.tanec.dlouhe-url}} "Tanec"
[VŠE]: http://www.sokolsestajovice.cz/{{site.data.oddil.vsestrannost.dlouhe-url}} "Všestrannost"
[RaD]: http://www.sokolsestajovice.cz/{{site.data.oddil.rd.dlouhe-url}} "Rodiče a děti"
[ŽEN]: http://www.sokolsestajovice.cz/{{site.data.oddil.zeny.dlouhe-url}} "Ženy"
[ZÁL]: http://www.sokolsestajovice.cz/{{site.data.oddil.zalesak.dlouhe-url}} "Zálesák"
[TR1]: http://www.sokolsestajovice.cz/{{site.data.oddil.trampoliny.dlouhe-url}} "Trampolíny – mladší"
[TR2]: http://www.sokolsestajovice.cz/{{site.data.oddil.trampoliny.dlouhe-url}} "Trampolíny – starší"
[FL1]: http://www.sokolsestajovice.cz/{{site.data.oddil.florbal.dlouhe-url}} "Florbal – mladší žáci"
[FL2]: http://www.sokolsestajovice.cz/{{site.data.oddil.florbal.dlouhe-url}} "Florbal – starší žáci"
[ZDR]: http://www.sokolsestajovice.cz/{{site.data.oddil.zdravotni.dlouhe-url}} "Zdravotní cvičení"
[TaR]: http://www.sokolsestajovice.cz/{{site.data.oddil.tanecky.dlouhe-url}} "Tanečky a rytmika"
[MÍČ]: http://www.sokolsestajovice.cz/{{site.data.oddil.micovky.dlouhe-url}} "Míčové hry"
[ZDP]: http://www.sokolsestajovice.cz/{{site.data.oddil.priroda.dlouhe-url}} "Zdravotní cvičení v přírodě"
[PK1]: http://www.sokolsestajovice.cz/{{site.data.oddil.parkour.dlouhe-url}} "Parkour – mladší"
[PK2]: http://www.sokolsestajovice.cz/{{site.data.oddil.parkour.dlouhe-url}} "Parkour – starší"
[MUŽ]: http://www.sokolsestajovice.cz/{{site.data.oddil.muzi.dlouhe-url}} "Oddíl mužů"


\* Zdravotní cvičení – sraz je před ZŠ Šestajovice v&nbsp;18:50.


## Aktivní oddíly

{% for oddil_hash in site.data.oddil %}{% assign oddil = oddil_hash[1] %}
* [{{oddil.nazev}} ({{oddil.vek}})]({{oddil.dlouhe-url}}){% endfor %}

---

Chtěli byste se stát členy některého z následujících oddílů?

* badatelský oddíl
* oddíl všestrannosti mužů
* sokoláček dramaťáček
* oddíl olympijského šplhu
* běžecký oddíl

[Kontaktujte nás!]({{ http://www.sokolsestajovice.cz }}/kontakt/){:.button}




