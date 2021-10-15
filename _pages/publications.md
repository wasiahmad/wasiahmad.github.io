---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

You can also find my articles on <a href="https://scholar.google.com/citations?user=YCHJZOMAAAAJ&hl=en">my Google Scholar profile</a>.

{% include base_path %}

<!-- {% for post in site.publications reversed %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h1 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h1>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %} -->

{% for y1 in 2021..2016 %}
  <h1 id="{{ year | slugify }}" class="year__title">2021</h1>
  {% for post in site.publications reversed %}
    {% capture year %}{{post.date | date: "%Y"}}{% endcapture %}
    {% if year == "2021" %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
{% endfor %}

