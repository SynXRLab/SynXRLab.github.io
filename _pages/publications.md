---
permalink: /publications/
title: "Publications"
author_profile: true
---

# 📖 Publications

<p class="pub-note"><strong>S Yan</strong> = Shuo Yan; * = corresponding author. Full list also on <a href="https://scholar.google.com/citations?user=FZwensUAAAAJ">Google Scholar</a>. XR demos and artworks are listed on the <a href="{{ '/works/' | relative_url }}">Works</a> page.</p>

{% assign papers = site.data.publications | where_exp: "p", "p.kind != 'work'" %}
{% assign by_year = papers | group_by: "year" %}
{% for g in by_year %}
<h2 class="pub-year">{{ g.name }}</h2>
<ul class="pub-list">
{% for p in g.items %}{% include pubs/row.html item=p %}{% endfor %}
</ul>
{% endfor %}
