---
permalink: /works/
title: "XR Demos and Artworks"
author_profile: true
---

# 😈 XR Demos and Artworks

<p class="pub-note">Immersive experiences, installations and demos shown at SIGGRAPH Asia (XR, Art Gallery, Art Papers, Posters), IEEE VR, IEEE VIS and Pacific Graphics. <strong>S Yan</strong> = Shuo Yan; * = corresponding author.</p>

{% assign works = site.data.publications | where_exp: "p", "p.kind != 'paper'" %}
<div class="work-grid">
{% for p in works %}{% include pubs/tile.html item=p %}{% endfor %}
</div>
