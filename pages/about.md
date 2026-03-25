---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi, I’m **{{ site.author.name }}** 👋  

I’m a Computer Science student at William & Mary graduating in May 2026. I’m interested in software engineering and AI, and I enjoy building applications that combine practical functionality with modern technologies.

I have experience working as an AI Code Annotator, where I wrote and analyzed code to support machine learning model training. This role helped me develop strong problem-solving skills and a deeper understanding of how code is interpreted by AI systems.

I’ve also built full-stack applications using technologies like Node.js, React, and PostgreSQL, including projects with user authentication, APIs, and database integration.

I’m currently seeking opportunities where I can apply my skills in software development and continue learning in real-world environments.

---

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
