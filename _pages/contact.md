---
layout: single
title: "Contact"
permalink: /contact/
author_profile: true
---

{% include base_path %}

## Contact Information

You can reach me through the following channels:

### Email
{% if site.author.email %}
  <i class="fas fa-fw fa-envelope icon-pad-right" aria-hidden="true"></i>
  <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>
{% endif %}

### GitHub
{% if site.author.github %}
  <i class="fab fa-fw fa-github icon-pad-right" aria-hidden="true"></i>
  <a href="https://github.com/{{ site.author.github }}">github.com/{{ site.author.github }}</a>
{% endif %}

### LinkedIn
{% if site.author.linkedin %}
  <i class="fab fa-fw fa-linkedin icon-pad-right" aria-hidden="true"></i>
  <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">linkedin.com/in/{{ site.author.linkedin }}</a>
{% endif %}
