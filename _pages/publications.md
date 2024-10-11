---
layout: archive
title: "Current Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

**Job Market Paper**

{% for post in site.research reversed %}
{% if post.title == 'How Much Can I Make? Insights on Belief Updating in the Labor Market (with Kenneth Chan)' %}
{% include archive-single.html %}
{% endif %}
{% endfor %}

**Other Research**

{% for post in site.research %}
{% if post.title == 'How Much Can I Make? Insights on Belief Updating in the Labor Market (with Kenneth Chan)' %}
{% elsif post.title == 'Baseball and life expectancy: evidence from linked historical data (with Joseph Price and Jacob Van Leeuwen)' %}
{% else %}
{% include archive-single.html %}
{% endif %}
{% endfor %}

**Publications**

{% for post in site.research %}
{% if post.title == 'Baseball and life expectancy: evidence from linked historical data (with Joseph Price and Jacob Van Leeuwen)' %}
{% include archive-single.html %}
{% endif %}
{% endfor %}


{% comment %}
{% for post in site.research reversed %}
{% include archive-single.html %}
{% endfor %}
{% endcomment %}