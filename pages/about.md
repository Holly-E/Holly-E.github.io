---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
Perhaps we have common interests such as neural network design, AWS or video games (I like world-building and lore).


<div class="row">
{% include about/skills.md title="Most fluent" source=site.data.programming-skills %}
{% include about/skills.md title="Additional skills" source=site.data.other-skills %}
</div> 

<div class="row">
{% include about/timeline.html %}
</div>