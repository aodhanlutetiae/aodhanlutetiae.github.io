---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

Here's a link

<a href="https://aodhanlutetiae.github.io/files/Leroledelalfabeto1600-1650-ODONNELL-compressed.pdf">"Le role de l'alfabeto"</a>

Coming soon ... a long list of lovely pieces of work!

**Odds n ends**
>[Search the Sonnets for a term](https://wssonnets.herokuapp.com/)

>[Running list of interesting datasets](https://docs.google.com/document/d/1jwWhnAXX1ctCH7C4Q3De6Za8PV5Xo61gCfeMVOeIUTg/edit#heading=h.akal3wpo8so1)

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
