---
layout: default
title: Coming Soon
permalink: /soon/
custom_color: green
custom_font: 
scroll_top_btn:
  enable: true

# CTA Section 1
cta1:
  enable: true
  bg_image: /assets/img/map.webp
  title: "Coming Soon"
  text: "Something great is on the way! Check back soon to see what we’ve been working on."
  button:
    label: "Coming Soon"
    url: "#"
    style: "btn btn-primary rounded-pill"
    
---
<section class="wrapper image-wrapper bg-auto no-overlay bg-image text-center py-14 py-md-16 bg-map" data-image-src="{{ page.cta1.bg_image }}">
  <div class="container py-0 py-md-18">
    <div class="row">
      <div class="col-lg-6 col-xl-5 mx-auto">
        <h2 class="display-4 mb-3 text-center">{{ page.cta1.title }}</h2>
        <p class="lead mb-5 px-md-16 px-lg-3">{{ page.cta1.text }}</p>
        <a href="{{ page.cta1.button.url }}" class="{{ page.cta1.button.style }}">{{ page.cta1.button.label }}</a>
      </div>
    </div>
  </div>
</section>
