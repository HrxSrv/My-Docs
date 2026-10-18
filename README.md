# My-Docs

LaTeX sources for my résumés. The one marked active is served on my portfolio.

- **Add a résumé:** add `resumes/<name>.tex`. The `<name>` becomes its id.
- **Choose the active one:** set `"active"` in `resumes.json` to an id, or use the portfolio's admin page.
- **PDFs:** on every push to `main`, the [Build resumes](.github/workflows/build-resumes.yml) workflow compiles each `.tex` with pdfLaTeX and publishes `<name>.pdf` to the [`pdfs`](../../tree/pdfs) branch.
