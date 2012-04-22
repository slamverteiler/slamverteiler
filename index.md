---
layout: default
---

Mehr über mich findest du auf meiner [MySlam.net Seite](http://www.myslam.net/de/slam-poet/4191).

Termine
=======
- Mittwoch, 5. Mai 2012:
  [Hamburg - Kultur Kost](http://www.myslam.net/de/poetry-slam-calendar/event/8308)

Blog
====

{% if site.posts %}
{% for post in site.posts limit:4 %}
- [{{post.title}}]({{post.url}}) | {{ post.date | date: "%d\. %B %Y" }} 

  {{ post.excerpt }} [>>&nbsp;mehr]({{ post.url }})
{% endfor %}
{% else %}
Im Moment gibt es hier nichts.
{% endif %}
