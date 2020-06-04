---
layout: page
title: Über mich
permalink: /about/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

## Kurzes Hallo! :) 

Hi, Du befindest dich auf meiner privaten Webseite. Hier kannst Du gerne stöbern und eventuell das eine oder andere Interessante finden. Lass es mich wissen, wenn Dir etwas besonders gut gefallen hat. Nun wünsche ich Dir viel Spaß!

</div>
