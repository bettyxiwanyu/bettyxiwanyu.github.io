---
layout: archive
title: "Publications 成果"
permalink: /publications/
author_profile: true
---

全部成果详见谷歌学术主页，以下为部分成果，点击标题链接阅读中文摘要。
{% if site.author.googlescholar %}
  <div class="wordwrap"> Below are selected articles. Click the title link to read English Abstracts. You can also find my full articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile </a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
