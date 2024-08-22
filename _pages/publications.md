---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This page includes a comprehensive list of every publication I have authored or co-authored.
Extra information on each publication, including the abstract and citation, can be found by clicking on the article title.

<!-- You can also find my articles on my <u><a href="{{author.googlescholar}}">Google Scholar</a></u> or <u><a href="{{author.researchgate}}">ResearchGate</a></u> profiles. -->

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
