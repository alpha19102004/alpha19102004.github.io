---
layout: none
permalink: /cv/
title: CV
nav: true
nav_order: 5
---

<!doctype html>
<html lang="en">
  <head>
    <meta http-equiv="refresh" content="0; url={{ '/assets/pdf/example_pdf.pdf' | relative_url }}">
    <script>
      window.location.replace("{{ '/assets/pdf/example_pdf.pdf' | relative_url }}");
    </script>
  </head>
  <body>
    <p>
      Redirecting to CV…
      <a href="{{ '/assets/pdf/example_pdf.pdf' | relative_url }}">Open the PDF</a>.
    </p>
  </body>
</html>
