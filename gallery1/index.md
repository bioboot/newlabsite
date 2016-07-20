---
layout: page
title: Gallery
---


<section class="features">
  <div class="grid">
    <div class="unit whole center-on-mobiles">
      {% for image in site.static_files %}
          {% if image.path contains 'img/slider' %}
              {% unless image.path contains 'thumb' %}
                  <a href="{{ site.baseurl }}{{ image.path }}" data-lightbox="pubimg">
                  <img src="{{ site.baseurl }}{{ image.path }}" class='resizegallery imghover' alt="image"/>
                  </a>
              {% endunless %}
          {% endif %}
      {% endfor %}
    </div>
  </div>
</section>
