---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

My accepted publications are listed below. For a full list of submitted and in preparation publications as well, please take a look at my CV. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{}}">my Google Scholar profile</a>.</u>
{% endif %}


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
