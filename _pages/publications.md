---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Francisco, F. A. & Nührenberg, P., Jordan, L. A. (2019). Low-cost, open-source solutions for animal
tracking in aquatic ecosystems. _in preparation_

Majoris, J. E., Francisco, F. A., Atema, J., & Buston, P. M. (2018). Reproduction, early development, and
larval rearing strategies for two sponge-dwelling neon gobies, Elacatinus lori and E. colini. _Aquaculture_ ,
_483_ , 286-295.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
