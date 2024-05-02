---
layout: archive
title: "Publications 成果"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap"> Below are recent selected articles. You can also find my full articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile </a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

全部成果详见谷歌学术主页，以下为近期成果。
