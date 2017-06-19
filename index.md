---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
---

Welcome to the CDN Speedlang Repository!

{% for page in site.pages %}
{% unless page.url == "/" or page.url == "/assets/main.css" or page.url == "/feed.xml" %}
* [{{page.title}}]({{page.url | prepend:site.baseurl }})
{% endunless %}
{% endfor %}
