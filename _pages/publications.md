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

<h1 style="margin: 1.5em 0px 1em; padding: 0px; color: brown;">Preprints</h1>
{% for post in site.publications reversed %}
  {% if post.venue == "Arxiv" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

{% assign publicationsByYear = site.publications | group_by_exp:"post", "post.date | date: '%Y'" %}
{% for year in publicationsByYear reversed %}
  <h1 style="margin: 1.5em 0px 1em; padding: 0px; color: brown;">{{ year.name }}</h1>
  {% for post in year.items %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}


