---
layout: archive
title: "Current Research"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

**Job Market Paper**

{% for post in site.publications reversed %}
{% if post.title == 'How Much Can I Make? Insights on Belief Updating in the Labor Market (with Kenneth Chan)' %}
{% include archive-single.html %}
{% endif %}
{% endfor %}

**Other Research**

{% for post in site.publications reversed %}
{% if post.title != 'How Much Can I Make? Insights on Belief Updating in the Labor Market (with Kenneth Chan)' %}
{% include archive-single.html %}
{% endif %}
{% endfor %}

<!---Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).--->
<!---{% for post in site.publications reversed %} {% include archive-single.html %} {% endfor %}--->