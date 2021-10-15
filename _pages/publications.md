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

{% assign publicationsByYear = site.publications | group_by_exp:"post", "post.date | date: '%Y'" %}
{% for year in publicationsByYear reversed %}
  <h1 id="{{ year | slugify }}" class="archive__title">{{ year.name }}</h1>
  {% for post in year.items %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}


