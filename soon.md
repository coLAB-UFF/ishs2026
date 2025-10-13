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
  bg_image: "/assets/img/illustrations/24503338_idea_01.webp"
  title: "Coming Soon"
  text: "Something great is on the way! Check back soon to see what we’ve been working on."
  button:
    label: "Back to Home"
    url: "https://colab-uff.github.io/ishs2026/"
    style: "btn btn-primary rounded-pill"
    
---
<div class="content-wrapper">
<header class="wrapper bg-light">
{% include components/navbar/navbar.html 
    topAlert=false
    wrapperClass="bg-soft-primary"
    classList="classic transparent navbar-light "
    logoAlt="logo-dark"
    otherClassList="ms-lg-4"
    otherBtn=true
    otherBtnClassList="btn btn-sm btn-primary rounded-pill"
    otherBtnText="Register Now"
    otherBtnLink="/contact/"     
%}
</header>
<!-- /header -->

<section class="wrapper image-wrapper bg-auto no-overlay bg-image text-center py-14 py-md-16 bg-map" data-image-src="">
  <div class="container py-0 py-md-18" style="background:url('/assets/img/illustrations/24503338_idea_01.webp');">
    <div class="row">
      <div class="col-lg-6 col-xl-5 mx-auto">
        <h2 class="display-4 mb-3 text-center">{{ page.cta1.title }}</h2>
        <p class="lead mb-5 px-md-16 px-lg-3">{{ page.cta1.text }}</p>
        <a href="{{ page.cta1.button.url }}" class="{{ page.cta1.button.style }}">{{ page.cta1.button.label }}</a>
      </div>
    </div>
  </div>
</section>

</div>




{% include components/footer/footer.html 
  style="default"
  bg_color="bg-navy"
  text_color="text-inverse" 
  cta=true
%}


