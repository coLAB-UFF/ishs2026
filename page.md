---
layout: default
title: Page ISHS 2026
permalink: /page/
custom_color: green
custom_font: 
scroll_top_btn:
  enable: true

# Header / Hero Section
hero:
  title: "Hello! This is Sandbox"
  subtitle: "A company turning ideas into beautiful things."
  bg_image: /assets/img/photos/bg12.jpg
  bg_color: "bg-gray"

# Services Section
services:
  title: What We Do?
  subtitle: The service we offer is specifically designed to meet your needs.
  service_items:
    - image: /assets/img/illustrations/i24.png
      image2x: /assets/img/illustrations/i24@2x.png
      title: Web Design
      text: Nulla vitae elit libero, a pharetra augue. Donec id elit non mi porta gravida at eget. Fusce dapibus tellus.
    - image: /assets/img/illustrations/i19.png
      image2x: /assets/img/illustrations/i19@2x.png
      title: Graphic Design
      text: Maecenas faucibus mollis interdum. Vivamus sagittis lacus vel augue laoreet. Sed posuere consectetur.
    - image: /assets/img/illustrations/i18.png
      image2x: /assets/img/illustrations/i18@2x.png
      title: 3D Animation
      text: Cras justo odio, dapibus ac facilisis in, egestas eget quam. Praesent commodo cursus magna scelerisque.

# Contact Section
contact:
  title: "Convinced yet? Let's make something great together."
  icon: "telemarketer"
  image: /assets/img/photos/about4.jpg
  image2x: /assets/img/photos/about4@2x.jpg
  info:
    - icon: "location-pin-alt"
      title: "Address"
      text: "Moonshine St. 14/05 Light City, London, United Kingdom"
    - icon: "phone-volume"
      title: "Phone"
      text: "00 (123) 456 78 90"
    - icon: "envelope"
      title: "E-mail"
      text: "sandbox@email.com"
      link: "mailto:sandbox@email.com"
---
<div class="content-wrapper">
<header class="wrapper bg-gray">
{% include components/navbar/navbar.html 
    classList="center-nav transparent navbar-light"
    otherClassList="w-100 d-flex ms-auto"
    otherLanguageSelect=true
    otherBtn=true
    otherBtnClassList="btn btn-sm btn-primary rounded-pill"
    otherBtnText="Contact"
    otherBtnLink="/contact"
%}
</header>
<!-- /header -->

{% include components/sections/about/hero.html %}
{% include components/sections/about/page.html %}

{% include components/footer/footer.html 
  style="default"
  container_padding="pt-16 pt-md-18 pb-13 pb-md-15"
  bg_color="bg-dark"
  text_color="text-inverse"
%}
</div>
