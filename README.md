# Brevo Ecommerce Brand Command Center

Static, self-contained dashboard, published to GitHub Pages so it opens without
any account.

`index.html` is generated: fonts, data and charts are inlined and the page makes
no external requests. Do not edit it by hand. It is rebuilt daily by the pipeline
in `~/claude fc/brand-command-center`.

Read-only by design. The write layer probes `http://127.0.0.1:8787`, which in any
visitor's browser is their own machine, so the page renders read-only for
everyone except on the machine running the console.
