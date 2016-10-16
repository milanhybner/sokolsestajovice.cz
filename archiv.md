---
layout: page
title: Archiv článků
permalink: /archiv/
---

{% for post in site.posts %}


## [{{ post.title }}]({{ post.url }})
{{ post.excerpt }} ~~ {% assign m = post.date | date: "%-m" %}_{{ post.date | date: "%-d" }}. {% case m %}{% when '1' %}ledna{% when '2' %}února{% when '3' %}března{% when '4' %}dubna{% when '5' %}května{% when '6' %}června{% when '7' %}července{% when '8' %}srpna{% when '9' %}září{% when '10' %}října{% when '11' %}listopadu{% when '12' %}prosince{% endcase %} {{ post.date | date: "%Y" }}_
{% endfor %}
