---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My main research interest lies in the field of the ecology and evolution of early vertebrates with a specific interest in evolutionary developmental biology. 
My approach combines insights from fossils with genetics to gain a more holistic understanding about the evolution of early vertebrates.
I have studied several groups of early jawless vertebrates, including conodonts, thelodonts and heterostracans; but also lampreys, one of the only recent jawless vertebrates. The methods I apply include:
- <b>Geochemical methods</b> like EDX (Energy Dispersive X-Ray Spectroscopy) and LA-ICP-MS to reconstruct the ecology of early vertebrates from their hard tissues as well as to reconstruct climate and environment 
- <b>Computational palaeobiological methods</b> like CFD (Computational Fluid Dynamics), FEA (Finite Element Analysis) and ROM (Range of Motion) to test hypotheses on the evolution of early vertebrates and their key features (especially teeth)
- <b>Molecular genetics methods</b> like transcriptomics to add a developmental perspective to my fossil studies



---

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
