---
title: Taxonomy
date: 2026-05-06 10:15:00 Z
layout: taxonomy
---

<div class="prose">
The taxonomy part of Digital Impacts Schema and Taxonomy (DIST) is a standardised categorisation system that can be applied across multiple impact dimensions. It's designed to create a common approach for structuring impacts so that information can become more comparable across different organisations and applications.
</div>

<div class="my-6">
  {% include DIST/taxonomy-overview.html %}

<h2>Impact dimensions</h2>

<div class="my-6">

{% tabs log %}
  {% tab log Default view %}
  <div class="my-8 info-box">
    The full, default taxonomy.
  </div>
  <div class="mb-8">
    {% include DIST/taxonomy-visual.html %}
  </div>
  {% endtab %}

  {% tab log Carbon %}
  <div class="my-8 info-box">
    A tailored view of the taxonomy to support categorisation with the carbon impact dimension.
  </div>
  <div class="mb-8">
  {% include DIST/taxonomy-visual.html dimension="carbon" %}
  </div>
  {% endtab %}

  {% tab log Water %}
  ```javascript
  pputs 'hello'
  ```
  {% endtab %}
{% endtabs %}

</div>
</div>



