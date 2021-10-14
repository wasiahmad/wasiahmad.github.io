---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

You can also find my articles on <a href="https://scholar.google.com/citations?user=YCHJZOMAAAAJ&hl=en">my Google Scholar profile</a>.

{% include base_path %}

{% for post in site.publications reversed %}
	{% include archive-single.html %}
{% endfor %}

<!-- <h1 style="color: red;">2021</h2>
{% for post in site.publications.2020 reversed %}
	{% include archive-single.html %} -->
