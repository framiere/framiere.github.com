---
layout: default
title: test index
---
# no-op

go to http://github.com/framiere 

# posts
{% for post in site.posts %}
{{ post.date | date_to_string }} [{{ post.title }}]({{ post.url }})
{% endfor %}


