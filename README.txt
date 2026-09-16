BNP Research Hub — insertable page block
=======================================

FILES
  bnp-hub.html            The block to insert. Site-wide Rutgers Accounting Web
                          header and menu are NOT included.
  bnp-hub-preview.html    The same markup wrapped in a minimal document, for
                          checking it in a browser before you paste it in.
  images/paper-02-hero.png  Card graphic for Paper 02. Upload to the page's
                          images/ directory (or change the <img src>).

INSERT
  Paste the whole contents of bnp-hub.html inside the site's main content
  area, below the site-wide header/menu. The three <link> tags at the top load
  Spectral and Archivo; move them into the site <head> if you prefer.

SCOPING
  Every style rule is scoped under .bnp-hub, so nothing leaks into the
  surrounding site and the site's own CSS will not restyle the block. All other
  styling is inline on the elements.

ADDING A THIRD PAPER
  Duplicate either <article id="paper-0X"> block, change the id, number, status
  pills, title, thesis line, three stats, authors, and two links. Then add a
  matching chip in the "Two papers in this series" row near the top (and update
  that label), and replace the muted "03 — Next in the series" row.

LINKS USED
  Paper 01 page  https://raw.rutgers.edu/bnp-disclosure-taxonomy
  Paper 01 PDF   https://raw.rutgers.edu/bnp-disclosure-taxonomy.pdf
  Paper 01 image https://raw.rutgers.edu/70wcars/New_BNP_pipeline_scarlet.png
  Paper 02 page  https://rutjo23.github.io/statblecoin-reporting/
  Paper 02 PDF   https://rutjo23.github.io/statblecoin-reporting/papers/Testing%20Machine%20Readable%20Compliance%20Validation%20Gaps%20and%20Omission%20Invariance%20in%20Stablecoin%20Reporting.pdf
