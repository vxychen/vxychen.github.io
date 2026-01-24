---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true

---
<!--{% include base_path %}-->


## Journal Articles

{% for post in site.journalpubs reversed %}
  {% include archive-single.html %}
{% endfor %}

## Conference Proceedings

{% for post in site.confpublications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Working Papers under Revision/Review

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}

<!-- ## Ongoing Projects

{% for post in site.working reversed %}
  {% include archive-single.html %}
{% endfor %} -->
