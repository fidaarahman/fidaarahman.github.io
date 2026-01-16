---
title: "Home"
layout: single
author_profile: true
permalink: /
---

## Publications

{% include publications.html %}

---

## Projects

{% assign sorted_projects = site.portfolio | sort: "date" | reverse %}
{% for project in sorted_projects %}
### [{{ project.title }}]({{ project.url }})

{{ project.excerpt }}

{% endfor %}

---

## Curriculum Vitae

You can view my full academic CV here:

👉 **[View CV](cv/)**
