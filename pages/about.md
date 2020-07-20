---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}**,<br>
To be edited soon. pretty soon test

<div class="row">
{% include about/skills.html title="Programming <br> Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Data <br> Skills" source=site.data.data-skills %}
{% include about/skills.html title="Visualization <br> Skills" source=site.data.visualization-skills %}
</div>

<br>
You can reach me at `info` [at] `balvindersingh.com`. 

<div class="row">
{% include about/timeline.html %}
</div>