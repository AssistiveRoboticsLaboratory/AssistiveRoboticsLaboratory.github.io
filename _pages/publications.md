---
layout: lab
title: "Publications"
permalink: /publications/
excerpt: "Research publications from the Assistive Robotics Laboratory at Clemson University, organized by topic."
---
<p class="large-copy">Our publications address task-agnostic control, assistance customization, stability augmentation, and the design of wearable and compliant robotic systems.</p>
<p>Journal articles and conference proceedings are organized by research topic, with links to available manuscripts. An additional publication record is available through <a href="{{ site.author.googlescholar }}">Ge Lv’s Google Scholar profile</a>.</p>
<div class="publication-topics">
{% for post in site.publications reversed %}
  <article class="publication-topic">
    <h2><a href="{{ site.baseurl }}{{ post.url | replace: ' ', '%20' }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
    <a class="text-link" href="{{ site.baseurl }}{{ post.url | replace: ' ', '%20' }}">View papers in this area →</a>
  </article>
{% endfor %}
</div>
