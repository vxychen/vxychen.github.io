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

{% for post in site.preprints %}
  {% include archive-single.html %}
{% endfor %}

## Ongoing Projects

Power gap and payment term in supply chains: how vertical and horizontal asymmetries shape fairness and efficiency

Designing end-to-end fairness optimization framework: from theory to practical insights

Equity-centric fair pricing in shared micromobility systems

Impact-aware sequential resource allocation

<!-- ## Ongoing Projects

{% for post in site.working reversed %}
  {% include archive-single.html %}
{% endfor %} -->
