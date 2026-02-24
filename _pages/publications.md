---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% for pub in site.data.publications %}
  <p>
    <strong>{{ pub.title }}</strong><br>
    {{ pub.authors }} ({{ pub.year }})<br>
    <em>{{ pub.journal }}</em><br>
    <a href="{{ pub.url }}">Paper</a>
  </p>
{% endfor %}
