---
layout: single
title: "Xiaofei Wang(Professor)"
author_profile: true
author: Xiaofei Wang   # 必须和 authors.yml 的 key 完全一致
---
Welcome to our group!



Our research focuses on machine learning, optimization, and their applications.
We are part of XXX University / Institute.

**News**
- 2025/01: One paper accepted by ...

- ## Recent Publications

<div class="entries-list">
{% assign pubs = site.publications | sort: "date" | reverse %}
{% for post in pubs limit:5 %}
  {% include archive-single.html type="list" %}
{% endfor %}
</div>

[Full publication list]({{ "/publications/" | relative_url }})

## Code & Projects

<div class="entries-grid">
{% assign projs = site.portfolio | sort: "date" | reverse %}
{% for post in projs limit:6 %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div>

[All projects]({{ "/portfolio/" | relative_url }})
