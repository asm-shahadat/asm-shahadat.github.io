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


* **A S M Shahadat Hossain**, Colin Brown, David Koop, and Tanu Malik, "Similarity-Based Assessment of Computational Reproducibility in Jupyter Notebooks," _ACM Conference on Reproducibility and Replicability (ACM REP ’25)_, Vancouver, BC, Canada, 2025.
* Md Saiful Islam, Talha Azaz, Raza Ahmad, **A S M Shahadat Hossain**, Furqan Baig, Shaowen Wang, Kevin Lannon, Tanu Malik, and Douglas Thain, "Backpacks for Notebooks: Enabling Containerized Notebook Workflows in Distributed Environments," _21st IEEE International Conference on e-Science (eScience ’25)_, Chicago, IL, USA, 2025.
* **A S M Shahadat Hossain**, "Customer Segmentation using Centroid Based and Density Based Clustering Algorithms," _3rd International Conference on Electrical Information and Communication Technology (EICT)_, Khulna, Bangladesh, 2017.

      

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
