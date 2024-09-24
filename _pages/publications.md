---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<!-- 
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
 -->

{% include base_path %}

My Google Scholar profile is [here](https://scholar.google.com/citations?user=DQg0PLgAAAAJ&hl=en).  

Conference Papers
-----------------

* **Hossain, ASM Shahadat**. "Customer Segmentation using Centroid Based and Density Based Clustering Algorithms." In _2017 3rd International Conference on Electrical Information and Communication Technology (EICT)_, pp. 1-6. IEEE, 2017.             
  **[Cited by: 43]**     

      
**Work in progress**:  

_I have been working on 2 conference papers to be submitted based on my [M.S. thesis](https://www.proquest.com/docview/3100751446) titled "Evaluating Computational Reproducibility of Jupyter Notebooks Using Machine Learning and Natural Language Processing."_

<!-- New style rendering if publication categories are defined -->
<!--
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

-->
