---
layout: default
title: Contact
---

<div class="contact-card">
  <div class="contact-row">
    <span class="contact-icon">✉</span>
    <a href="mailto:marcovmaselli@gmail.com">marcovmaselli@gmail.com</a>
  </div>
  <div class="contact-row">
    <span class="contact-icon">🏛</span>
    <a href="mailto:marcovincenzo.maselli@unifi.it">marcovincenzo.maselli@unifi.it</a>
    <span style="font-size:0.82rem; color:#64748b;">(institutional)</span>
  </div>
</div>

## Profiles

<div class="social-links">
  <a class="social-link" href="https://github.com/marcovmaselli"><i class="fab fa-github"></i> GitHub</a>
  <a class="social-link" href="https://www.linkedin.com/in/mv-maselli/"><i class="fab fa-linkedin-in"></i> LinkedIn</a>
  <a class="social-link" href="https://orcid.org/0009-0004-0893-6513"><i class="ai ai-orcid"></i> ORCID</a>
  <a class="social-link" href="https://scholar.google.com/citations?user=GdpGVaUAAAAJ"><i class="ai ai-google-scholar"></i> Google Scholar</a>
</div>

## Send a message

<form action="https://formspree.io/f/xeebgale" method="POST" class="contact-form">
  <div class="form-group">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" required placeholder="Your name">
  </div>
  <div class="form-group">
    <label for="email">Email</label>
    <input type="email" id="email" name="email" required placeholder="your@email.com">
  </div>
  <div class="form-group">
    <label for="message">Message</label>
    <textarea id="message" name="message" rows="5" required placeholder="Write your message here..."></textarea>
  </div>
  <button type="submit" class="cv-download-btn" style="border:none; cursor:pointer;">Send message →</button>
</form>

<style>
.contact-form { max-width: 560px; margin-top: 1rem; }
.form-group { margin-bottom: 1.2rem; }
.form-group label {
  display: block;
  font-size: 0.85rem;
  font-weight: 600;
  color: #0f172a;
  margin-bottom: 0.4rem;
}
.form-group input,
.form-group textarea {
  width: 100%;
  padding: 0.65rem 0.9rem;
  font-family: 'Inter', sans-serif;
  font-size: 0.92rem;
  color: #1e293b;
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  border-radius: 8px;
  transition: border-color 0.2s, box-shadow 0.2s;
  outline: none;
}
.form-group input:focus,
.form-group textarea:focus {
  border-color: #0d9488;
  box-shadow: 0 0 0 3px rgba(13,148,136,0.12);
  background: #fff;
}
.form-group textarea { resize: vertical; }
</style>
