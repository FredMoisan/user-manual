# Experiment platform: user manual

The user manual of the experiment platform, for participants and researchers: [manual.md](manual.md).

This repository holds the documentation only. The platform's code is not published here.

## Images

Screenshots go in the `images/` folder and are linked with relative paths, for example:

```markdown
![The admin panel](images/admin-panel.png)
```

Before adding a screenshot, check that it shows no real participant, email address, server address or other private
detail.

## Making a PDF

The manual converts to PDF with [pandoc](https://pandoc.org/) and a LaTeX engine (for example
[MiKTeX](https://miktex.org/) on Windows, or TeX Live). From this folder:

```bash
pandoc manual.md -o manual.pdf --toc --toc-depth=2 -V geometry:margin=2.5cm -V colorlinks=true -V linkcolor=blue --resource-path=.
```

- `--toc` adds a table of contents; the headings already carry their numbers, so `--number-sections` is not needed.
- Without LaTeX, `--pdf-engine=wkhtmltopdf` (or `weasyprint`) makes the PDF from HTML instead.
- For a Word file, use `-o manual.docx` instead.
