---
layout: archive
title: "Research"
permalink: /research/
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

Power Gap and Payment Term in Supply Chains: How Vertical and Horizontal Asymmetries Shape Fairness and Efficiency

Designing End-to-End Fairness Optimization Framework: from Theory to Practical Guidance

Equity-Centric Fair Pricing in Shared Micromobility Systems

Impact-Aware Sequential Resource Allocation

<!-- ## Ongoing Projects

{% for post in site.working reversed %}
  {% include archive-single.html %}
{% endfor %} -->
