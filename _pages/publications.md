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

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=YCHJZOMAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% include base_path %}

<h1 style="color: red;">2021</h2>
{% for post in site.publications.conference reversed %}
	{% include archive-single.html %}
