---
layout: page
title: Résumé
subtitle: A concise version of the work. Print or save it as a PDF.
---

<div class="resume-toolbar no-print">
  <button class="btn btn-primary" type="button" onclick="window.print()">
    <i class="fas fa-print" aria-hidden="true"></i> Print / save as PDF
  </button>
  <a class="btn btn-ghost" href="mailto:debarshikundu0@utexas.edu">
    <i class="fas fa-envelope" aria-hidden="true"></i> Email me
  </a>
</div>

<div class="resume">

  <div class="resume-contact">
    <a href="mailto:debarshikundu0@utexas.edu">debarshikundu0@utexas.edu</a>
    <span class="resume-sep">·</span>
    <a href="https://github.com/debarshikundu">github.com/debarshikundu</a>
    <span class="resume-sep">·</span>
    <a href="https://linkedin.com/in/debarshi-kundu-19145636">linkedin.com/in/debarshi-kundu-19145636</a>
  </div>

  <section class="resume-section">
    <h2>Summary</h2>
    <p>
      Computer science student and software developer with experience across desktop, mobile, backend,
      and data projects. Comfortable moving from a vague problem to a working prototype, and from a
      prototype to something documented and reproducible. Interested in security engineering and
      systems-level work.
    </p>
  </section>

  <section class="resume-section">
    <h2>Education</h2>
    <div class="resume-item">
      <div class="resume-item-head">
        <h3>The University of Texas at Austin</h3>
        <span class="resume-date">B.S. Computer Science</span>
      </div>
      <p class="resume-detail">
        Relevant coursework: data structures, algorithms, computer systems, databases, and software engineering.
      </p>
    </div>
  </section>

  <section class="resume-section">
    <h2>Selected projects</h2>

    <div class="resume-item">
      <div class="resume-item-head">
        <h3><a href="{{ '/projects/cryptor/' | relative_url }}">cryptor</a></h3>
        <span class="resume-date">Python</span>
      </div>
      <ul class="resume-list">
        <li>Built a command-line encryption and decryption tool focused on correct byte handling and explicit failure modes.</li>
        <li>Documented the difference between encoding and encryption, and the limits of educational cryptography.</li>
      </ul>
    </div>

    <div class="resume-item">
      <div class="resume-item-head">
        <h3><a href="{{ '/projects/tracking-experiments/' | relative_url }}">TrackingExperiments</a></h3>
        <span class="resume-date">C# / .NET</span>
      </div>
      <ul class="resume-list">
        <li>Developed a real-time desktop prototype for psychophysics experiments involving moving-object tracking.</li>
        <li>Designed the experiment loop and data capture with reproducibility and lab deployment in mind.</li>
      </ul>
    </div>

    <div class="resume-item">
      <div class="resume-item-head">
        <h3><a href="{{ '/projects/tesla-gamestop-dashboard/' | relative_url }}">Tesla &amp; GameStop Stock Dashboard</a></h3>
        <span class="resume-date">Python / Jupyter</span>
      </div>
      <ul class="resume-list">
        <li>Collected and cleaned historical stock and quarterly revenue data for two companies.</li>
        <li>Built an interactive dashboard comparing price movement with revenue growth.</li>
      </ul>
    </div>

    <div class="resume-item">
      <div class="resume-item-head">
        <h3><a href="{{ '/projects/flix/' | relative_url }}">Flix</a></h3>
        <span class="resume-date">Swift / UIKit</span>
      </div>
      <ul class="resume-list">
        <li>Built an iOS movie browser backed by the TMDB REST API, including poster grid and detail views.</li>
        <li>Handled asynchronous image loading, loading states, and API failure cases.</li>
      </ul>
    </div>
  </section>

  <section class="resume-section">
    <h2>Experience</h2>
    <div class="resume-item">
      <div class="resume-item-head">
        <h3>Independent software projects</h3>
        <span class="resume-date">2023 — present</span>
      </div>
      <ul class="resume-list">
        <li>Design, build, and document small software projects across four languages and platforms.</li>
        <li>Practise security fundamentals through CTF challenges and retired lab machines.</li>
        <li>Write technical explanations of completed work for a general audience.</li>
      </ul>
    </div>
    <!-- Add internships, research, teaching, or campus roles here. -->
  </section>

  <section class="resume-section">
    <h2>Skills</h2>
    <dl class="resume-skills">
      <div><dt>Languages</dt><dd>Python, Java, C#, Swift, JavaScript, HTML/CSS, SQL</dd></div>
      <div><dt>Tools</dt><dd>Git, GitHub, VS Code, Jupyter, pandas, Plotly, Linux/macOS</dd></div>
      <div><dt>Security</dt><dd>CTF methodology, web application testing, Burp Suite, Wireshark, basic cryptography</dd></div>
      <div><dt>Practices</dt><dd>Technical writing, reproducible analysis, debugging, version control</dd></div>
    </dl>
  </section>

</div>

<p class="resume-note no-print">
  Prefer a PDF? Use the print button above and choose “Save as PDF”.
</p>
