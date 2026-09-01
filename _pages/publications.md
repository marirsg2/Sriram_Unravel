---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<p class="intro-text">
  A full list of my peer-reviewed conference proceedings, journal articles, and workshop papers in Automated Planning, Reinforcement Learning, Generative AI, and Human-AI Interaction. You can also view my live citation metrics on <a href="https://scholar.google.com/citations?user=So86Wl4AAAAJ&hl=en" target="_blank" class="btn btn--info btn--small"><i class="fa fa-graduation-cap"></i> Google Scholar Profile</a>.
</p>

<div class="award-highlights-banner">
  <strong>Key Highlights:</strong>
  <ul>
    <li>🏆 <strong>Best Industry Paper Award</strong> — ACM International Conference on AI in Finance (ICAIF 2023)</li>
    <li>🎙️ <strong>Oral Presentation (Top 2% of accepted papers)</strong> — AAAI Conference on Artificial Intelligence (AAAI-24)</li>
    <li>🎖️ <strong>Top Performer</strong> — DARPA SAIL-ON Novelty Handling in Open World Environments</li>
  </ul>
</div>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
