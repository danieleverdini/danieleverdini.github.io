---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
classes: cv-page wide
---

<p>
  <a class="btn btn--primary" href="{{ '/files/cv.pdf' | relative_url }}" target="_blank" rel="noopener">
    Download CV (PDF)
  </a>
</p>

<div class="pdf-container">
  <object
    data="{{ '/files/cv.pdf' | relative_url }}"
    type="application/pdf"
    width="100%"
    height="100%">
    <embed src="{{ '/files/cv.pdf' | relative_url }}" type="application/pdf"/>
    <!-- Fallback for browsers that can't embed PDFs -->
    <p>
      Your browser can’t display PDFs inline.
      <a href="{{ '/files/cv.pdf' | relative_url }}" target="_blank" rel="noopener">Open the CV</a>.
    </p>
  </object>
</div>
