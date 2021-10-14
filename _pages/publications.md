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

{% for post in site.publications reversed %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h1>{{ year }}</h1>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
<!--   {% include archive-single.html %} -->
  <ul class="posts-in-year">
    <li><p><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}    </a> &mdash; {{ post.date | date: "%B %d" }}</p></li>
  </ul>
{% endfor %}
