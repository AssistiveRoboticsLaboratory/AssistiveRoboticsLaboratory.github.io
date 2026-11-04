---
layout: lab
title: "Human-centered robotics for assistance and augmentation"
lab_home: true
permalink: /
excerpt: "The Assistive Robotics Laboratory at Clemson University investigates control, customization, design, and evaluation of human-centered robotic systems for assistance across daily activities."
redirect_from:
  - /about/
  - /about.html
---
<section class="hero">
  <div class="hero-copy">
    <p class="eyebrow">Clemson University · Assistive Robotics Laboratory</p>
    <h1>Human-centered robotics for assistance and augmentation.</h1>
    <p class="lede">We investigate control, customization, design, and evaluation methodologies for robotic systems that assist humans across daily activities.</p>
    <div class="actions"><a class="button primary" href="{{ site.baseurl }}/Research/">Explore our research <span aria-hidden="true">↗</span></a><a class="button" href="{{ site.baseurl }}/publications/">Publications</a></div>
  </div>
  <figure class="hero-image"><img src="{{ site.baseurl }}/images/Labview.jpg" alt="A panoramic view of the Assistive Robotics Laboratory at Clemson University"><figcaption>Assistive Robotics Laboratory · Clemson University</figcaption></figure>
</section>
<section class="section mission">
  <div class="wrap lab-overview">
    <div class="lab-mission"><p class="eyebrow">ARL · Research mission</p><h2>Robotic assistance across daily activities.</h2><p class="large-copy">The mission of the Assistive Robotics Laboratory is to develop agile, versatile robotic systems to assist humans across daily activities.</p><p>Our research connects task-agnostic control and customization, wearable device prototyping, and biomechanics studies. We investigate these directions through mathematical analysis, simulation, hardware development, and experimental evaluation.</p><a class="text-link" href="{{ site.baseurl }}/Research/">ARL research program →</a></div>
    <aside class="director-profile" aria-labelledby="director-name"><img src="{{ site.baseurl }}/images/Ge.jpg" alt="Ge Lv, principal investigator" loading="lazy"><div><p class="eyebrow">Laboratory director</p><h3 id="director-name">Ge Lv <span>(吕阁), PhD</span></h3><p>Assistant Professor, Mechanical Engineering and Bioengineering<br>Faculty Scholar, School of Health Research<br>Clemson University</p><a class="text-link" href="{{ site.baseurl }}/team/">Research personnel →</a><a class="text-link" href="mailto:glv@clemson.edu">Contact Dr. Lv</a></div></aside>
  </div>
</section>
<section class="section research" id="research">
  <div class="wrap"><p class="eyebrow">ARL research program</p><h2>Control, prototyping, and biomechanical evaluation</h2>
    <div class="research-grid">
      <article><span class="index">01 / Control and Customization</span><h3>Task-Agnostic Control and Customization</h3><p>Development of task-agnostic control paradigms and human-in-the-loop customization frameworks for robotic assistance across users and daily activities.</p><a class="text-link" href="{{ site.baseurl }}/Research/#personalization">Explore control and customization →</a></article>
      <article><span class="index">02 / Design</span><h3>Wearable Device Development and Prototyping</h3><p>Design, development, and prototyping of user-friendly wearable robotic devices for assistance of human motion.</p><a class="text-link" href="{{ site.baseurl }}/Research/#prosthetics">Explore device development →</a></article>
      <article><span class="index">03 / Evaluations</span><h3>Biomechanics Study</h3><p>Experimental validation and biomechanical studies to characterize human movement, physical human–robot interaction, and the effects of robotic assistance.</p><a class="text-link" href="{{ site.baseurl }}/Research/#evaluations">Explore biomechanical evaluation →</a></article>
    </div>
  </div>
</section>
<section class="section feature">
  <div class="wrap feature-grid"><img src="{{ site.baseurl }}/images/Clemson%20Interview.jpg" alt="Clemson World feature on the laboratory’s wearable robotics research" loading="lazy"><div><p class="eyebrow">ARL in Clemson World</p><h2>One step at a time.</h2><p>Clemson World features our research on wearable robotic systems for assistance of human locomotion.</p><a class="text-link" href="https://clemson.world/one-step-at-a-time/">Read the story →</a></div></div>
</section>
<section class="section" id="news">
  <div class="wrap section-grid"><div><p class="eyebrow">From the laboratory</p><h2>Recent news</h2></div><div>
    {% assign news_items = site.data.lab_news | slice: 0, 8 %}{% include lab-news.html %}
    <details class="news-archive"><summary>More laboratory news · 2020–2024</summary><div class="archive-content">{% assign news_items = site.data.lab_news | slice: 8, 1000 %}{% include lab-news.html %}</div></details>
  </div></div>
</section>
<section class="section home-outreach">
  <div class="wrap section-grid"><div><p class="eyebrow">Education and outreach</p><h2>Research training and engineering education</h2></div><div><p class="large-copy">Our educational activities include faculty instruction, student design advising, and undergraduate research mentorship.</p><p>Dr. Lv has participated in Clemson’s Emerging Scholars and EUREKA! programs and serves as faculty advisor to the Clemson Baja Team. Undergraduate researchers also contribute to the laboratory through Creative Inquiry.</p><a class="text-link" href="{{ site.baseurl }}/outreach/">Outreach and educational activities →</a></div></div>
</section>
