---
layout: default
title: Publications
---

<div style="display:flex; align-items:center; gap:1rem; margin-bottom:2rem; flex-wrap:wrap;">
  <a href="{{ '/pub.bib' | relative_url }}" download class="cv-download-btn">
    ↓ Download pub.bib
  </a>
  <a href="https://scholar.google.com/citations?user=GdpGVaUAAAAJ" target="_blank" class="social-link">
    Google Scholar profile →
  </a>
</div>

<script src="https://bibbase.org/show?bib=https://raw.githubusercontent.com/marcovmaselli/marcovmaselli.github.io/main/pub.bib&theme=simple&jsonp=1"></script>

<style>
/* BibBase integration overrides */
.bibbase_paper {
  padding: 1.4rem 1.6rem;
  margin-bottom: 1rem;
  background: #ffffff;
  border: 1px solid #e2e8f0;
  border-radius: 10px;
  transition: box-shadow 0.2s, transform 0.2s;
  font-size: 0.95rem;
  line-height: 1.6;
}
.bibbase_paper:hover {
  box-shadow: 0 4px 20px rgba(0,0,0,0.08);
  transform: translateY(-2px);
}
.bibbase_paper .title {
  font-weight: 600;
  color: #0f172a;
  font-size: 1rem;
}
.bibbase_paper .author {
  color: #334155;
}
.bibbase_paper .author b,
.bibbase_paper .author strong {
  color: #0f172a;
}
.bibbase_year { color: #0d9488; font-weight: 600; font-size: 0.85rem; text-transform: uppercase; letter-spacing: 0.05em; }
#bibbase_header { display: none; }
</style>
