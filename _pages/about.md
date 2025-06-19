---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I recently earned my **Bachelor of Science** degree in **Computer Science** from the **University of California, Irvine** (**Cum Laude**, GPA 3.93), where I specialized in **artificial intelligence** and **machine learning**. My research interests lie broadly in **probabilistic machine learning**, with a particular focus on **generative models**, **representation learning**, and their intersections with **applied mathematics**. I’m especially excited about advancing the theoretical foundations and practical capabilities of **diffusion models** and other forms of **generative AI**, with the aim of enabling new tools for science and discovery.

My academic work spans areas such as **graphical models**, **causal reasoning**, and **deep reinforcement learning**, and I recently co-authored **PoseBench3D**, a benchmarking framework for **3D human pose estimation**. Going forward, I hope to design **generative** and **diffusion models** that learn **robust representations** and translate theoretical advances into practical gains for **scientific discovery**.


<div style="margin: 2em 0; display: flex; align-items: center; gap: 1em; flex-wrap: wrap;">
  <a href="/files/Bryan_Vela_CV.pdf" target="_blank" style="
    display: inline-block;
    padding: 0.6em 1.2em;
    font-weight: bold;
    color: white;
    background-color: #007acc;
    text-decoration: none;
    border-radius: 6px;
    transition: background-color 0.2s ease-in-out;">
    Download Academic CV
  </a>

  <div style="font-size: 0.85em; color: var(--global-text-color-dark);">
    <strong>(Updated June 2025)</strong>
  </div>
</div>




Publications & Preprints
======
<p>
  C = Conference, J = Journal, S = In-Submission, * = Equal Contribution
</p>


<hr style="border-top: 2px solid #444; margin-top: 6px; margin-bottom: 12px;" />


{% assign sorted_pubs = site.publications | sort: 'date' | reverse %}
{% for post in sorted_pubs %}
  {% assign authors_formatted = post.authors | replace: 'Bryan Vela*', '<strong>Bryan Vela*</strong>' %}

  <div style="margin-bottom: 2.4em; display: flex; align-items: flex-start;">
    <div style="min-width: 4em; font-weight: bold; margin-right: 0.8em;">[{{ post.label }}]</div>
    <div style="line-height: 1.6;">
      <div style="font-weight: bold;">{{ post.title }}</div>
      <div>{{ authors_formatted }}.</div>
      <div><em>{{ post.venue }}</em></div>
      <div>
        {% if post.paperurl %}
          <a href="{{ post.paperurl }}" target="_blank">[Paper]</a>
        {% endif %}
        {% if post.codeurl %}
          <a href="{{ post.codeurl }}" target="_blank">[Code]</a>
        {% endif %}
      </div>
    </div>
  </div>
{% endfor %}



<div style="margin-top: 5em;"></div>



Selected Awards
======
<ul style="margin-top: 0.2em; margin-bottom: 1.5em; padding-left: 1.2em; line-height: 1.25; list-style-position: outside;">
  <li style="margin-bottom: 0.6em;">
    <strong>Jack Kent Cooke Transfer Scholarship</strong><br>
    <em>Jack Kent Cooke Foundation</em><br>
    Nationally awarded scholarship totaling <strong>$165,000</strong> for academic excellence and leadership
  </li>
  <li><strong>Graduated Cum Laude</strong>, UC Irvine</li>
  <li><strong>Phi Theta Kappa Honor Society Scholar</strong></li>
  <li><strong>Dean’s List – All Quarters at UC Irvine</strong></li>
  <li><strong>Howmet Aerospace Scholarship for STEM</strong></li>
  <li><strong>Edison Scholars Scholarship × 2</strong></li>
  <li><strong>Inclusive Excellence Latinx Alliance Scholarship</strong></li>
  <li><strong>Robert Sprague STEM Scholarship × 2</strong></li>
</ul>


