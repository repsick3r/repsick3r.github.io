---
title: Stuff
permalink: /stuff/
---

# Stuff

<div class="cards">
{% for work in site.data.works %}{% include work-card.html work=work %}{% endfor %}
</div>
