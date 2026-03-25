---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi, I’m **{{ site.author.name }}** 👋  

I’m a Computer Science student at William & Mary graduating in May 2026. I’m interested in software engineering and AI, and I enjoy building applications that combine practical functionality with modern technologies.

I have experience building many websites. This helped me develop strong problem-solving skills and a deeper understanding of how to efficiently and effectively build software.

I’ve also built full-stack applications using technologies like Node.js, React, and PostgreSQL, including projects with user authentication, APIs, and database integration.

---

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
