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

## Professional Experience

### AI & Android Developer  
**Freelance / Independent Projects**  
Islamabad, Pakistan  

- Developed AI-powered Android applications using Deep Learning and Computer Vision  
- Integrated ML models into mobile apps using TensorFlow Lite  
- Worked with Kotlin, Python, OpenCV, Firebase, and REST APIs  

### Software Engineering Graduate  
- Strong foundation in software engineering principles  
- Experience with AI, Machine Learning, and intelligent systems  
- Focused on real-world problem solving using modern technologies
