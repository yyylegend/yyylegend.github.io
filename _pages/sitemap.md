---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

本页面列出了本站的主要页面与内容索引。 

<h2>Pages</h2>
{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}

{% capture written_label %}'None'{% endcapture %}

{% if site.publications %}
## Publications
{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

{% if site.portfolio %}
## Projects
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}
