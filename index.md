---
layout: default
title: ISHS 2026
permalink: /
custom_color: green
custom_font: urbanist
scroll_top_btn:
  enable: true

# Banner Section
banner:
  enable: true
  text: "Text"

# Hero Section
hero:
  title: International Society for Humor Studies<br><span class="rotator-fade text-primary">Niterói, Brazil <br />July, 6 to 10, 2026</span>
  subtitle: Where the <a href="./zueira">zueira</a> never ends.
  button:
    label: Register Now
    url: "register"
    class: btn btn-lg btn-primary rounded-pill
  image: "./assets/img/illustrations/ishs_logo.webp"
  image2x: ""
  trust_text: The Fluminense Federal University proudly presents, for the first time in the Majority World...
  
# Services Section
services:
  title: Explore, Connect, and Be Inspired
  subtitle: Stay up to date with the conference's main activities.
  service_items:
    - image: /assets/img/illustrations/i24.png
      image2x: /assets/img/illustrations/i24@2x.png
      title: Keynote Speakers and Roundtables
      text: Join leading scholars and practitioners for thought-provoking talks that set the tone for our shared debates and inspire new research directions.
    - image: /assets/img/illustrations/i19.png
      image2x: /assets/img/illustrations/i19@2x.png
      title: Panels
      text: Engage in focused discussions with peers who share your research interests, fostering collaboration and advancing specialized topics.
    - image: /assets/img/illustrations/i18.png
      image2x: /assets/img/illustrations/i18@2x.png
      title: Cultural Activities
      text: Experience the local culture through curated events that blend learning, art, and community in a welcoming and vibrant atmosphere.
      
# Strategy Section
strategy:
  title: Our Important Steps
  subtitle: Niterói will be the epicenter of humor studies for a week.
  text: The International Society for Humor Studies (ISHS) is the leading scholarly association dedicated to promoting interdisciplinary research on humor in its multiple dimensions, involving researchers from diverse fields such as communication, psychology, sociology, linguistics, philosophy, law, the arts, education, and health.
  text2: In the year marking 50 years since the first interdisciplinary humor studies conference in 1976, the event will be held in Brazil for the first time. Don’t miss it!
  button:
    label: Register Now
    url: "register"
    class: btn btn-primary rounded-pill
  steps:
    - number: "01"
      title: Register
      text: Ensure your participation in the conference and access all academic and cultural sessions!
    - number: "02"
      title: Submit
      text: Present your research and join the ongoing exchange of ideas within our academic community.
    - number: "03"
      title: Follow the Program
      text: Consult the schedule for panels, keynotes, and cultural activities throughout the event.

# Why Choose Us Section
why_us:
  title: Why Choose Us?
  subtitle: We bring solutions to make life easier.
  image: /assets/img/illustrations/i22.png
  image2x: /assets/img/illustrations/i22@2x.png
  accordion_items:
    - title: Professional Design
      text: Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Cras mattis consectetur purus sit amet fermentum. Praesent commodo cursus magna, vel.
      active: true
    - title: Top-Notch Support
      text: Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Cras mattis consectetur purus sit amet fermentum. Praesent commodo cursus magna, vel.
    - title: Header and Slider Options
      text: Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Cras mattis consectetur purus sit amet fermentum. Praesent commodo cursus magna, vel.

# Company Facts Section
company_facts:
  title: Conference Numbers
  subtitle: We look forward to welcoming you in July 2026
  text: Based on previous years, our expectations are high.
  counters:
    - icon: uil uil-presentation-check
      count: 300+
      text: Expected Submissions
    - icon: uil uil-user-check
      count: 500+
      text: Scholars and Students
    - icon: uil uil-trophy
      count: 4+
      text: Awards

# Team Section
team:
  
# Projects Section
projects:
  title: Latest Projects
  subtitle: Check out some of our awesome projects with creative ideas and great design.

# Testimonials Section
testimonials:
  title: Happy Customers
  subtitle: Don't take our word for it. See what customers are saying about us.
  

# FAQ Section
faq:
  title: FAQ
  subtitle: If you don't see an answer to your question, you can send us an email from our contact form.
  text: First-timer?
  button:
    label: All FAQ
    url: "faq"
    class: btn btn-primary rounded-pill
  faq_items:
    - title: Do I have to be a member of the ISHS to join the conference?
      text: No. But there is a big discount in the registration fee for members of the ISHS, and considering that being an associate member of the ISHS costs only US$ 30 a year, plus all the benefits coming with this membership, we invite you to consider joining the society.
    - title: Are the conference activities transmitted online?
      text: No. The papers and poster sessions, the roundtables and the keynote lectures are all exclusively in person. There will be a special conference, entirely online, before the main event, dedicated to papers about humor in the Global South. More info about this soon.
    - title: Are there special fees for delegates from the Global South?
      text: Yes. Students, professors and professionals from countries of the Global South are entitled to lower registration fees. More info about this soon.
    - title: What are the languages of the conference?
      text: There will be lectures in English and Portuguese, with simultaneous translation into Portuguese and English. Most of the papers will be presented in English, but there will be sessions with papers in Portuguese and Spanish. Check out our program later.

# Footer CTA
footer_cta:
  title: Join our community by registering for the conference, submitting your work, and following our sessions and activities.
  button:
    label: Register Now
    url: "register"
    class: btn btn-primary rounded-pill
    
---
<div class="content-wrapper">
<header class="wrapper bg-light">
  
<div class="alert alert-success alert-icon" role="alert">
  <i class="uil uil-check-circle"></i> Welcome to the 36th ISHS Conference Official Website.
</div>
  
{% include components/navbar/navbar.html 
    topAlert=false
    wrapperClass="bg-soft-primary"
    classList="classic transparent navbar-light "
    logoAlt="logo-dark"
    otherClassList="ms-lg-4"
    otherBtn=true
    otherBtnClassList="btn btn-sm btn-primary rounded-pill"
    otherBtnText="Register Now"
    otherBtnLink="register/"     
%}
</header>
<!-- /header -->

{% include components/sections/demo21/hero.html %}
{% include components/sections/demo21/services.html %}
{% include components/sections/demo21/strategy.html %}

<section class="wrapper bg-light">
  <div class="container py-14 py-md-16">
    <div class="row gx-lg-8 gx-xl-12 gy-10">
      <div class="col-lg-6">
        <figure><img class="w-auto" src="/assets/img/photos/facilities1.jpg" alt="" /></figure>
      </div>
      <div class="col-lg-6">
        <h2 class="display-4 mb-3">Welcome to Niterói, Brazil</h2>
        <p class="lead fs-lg mb-6 pe-xxl-10">The 2026 ISHS Conference will take place at Fluminense Federal University, in Niterói, Brazil

.</p>
        Niterói, a neighboring city to the internationally renowned Rio de Janeiro, is home to the main campus of Fluminense Federal University (Universidade Federal Fluminense, or simply UFF), one of Brazil’s most prestigious institutions. We look forward to seeing you at the first humor conference in Latin America, and the first in the Global South.
          
      </div>
    </div>
  </div>
</section>

{% include components/sections/demo21/why-us.html %}
{% include components/sections/demo21/company-facts.html %}
{% include components/sections/demo21/faq.html %}

</div>
{% include components/footer/footer.html 
  style="default"
  bg_color="bg-navy"
  text_color="text-inverse" 
  cta=true
%}
