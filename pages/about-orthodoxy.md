---
title: About Orthodoxy
layout: default
---

## About Orthodoxy #

There is a wealth of information about Orthodoxy on the internet.
So much in fact, that one may not know where to begin.
Our goal here is not to duplicate information, nor to overwhelm,
but rather to give an inquirer a starting point to help them learn more about
the ancient Orthodox Christian Faith.
Hopefully, the links below will serve that purpose.

<ul class="list-group">
  {% for link in site.data.about_orthodoxy %}
    <li class="list-group-item">
      <a href="{{ link.href }}" target="_blank">{{ link.title }}</a>
    </li>
  {% endfor %}
</ul>