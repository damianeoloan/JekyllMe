---
layout: post
title:  "Welcome to JekyllMe"
date:   2016-02-16
---
JekyllMe is a free Jekyll theme for personal websites.

Your website includes a CV / resume, portfolio slideshow, blog and contact form, wrapped in a single page.

{% for experience in site.resume-items.experiences %}
  {{ forloop.index }}
{% endfor %}

[How to set up your website](/setup)
