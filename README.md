# DoctoralThesisTexTemplate
LaTeX Template for Doctoral Theses. NO guarantee that this is up to date with current UNC-CH Graduate School's formatting guidelines.

## Rmarkdown usage

Download the template.tex file (or clone this repository).

In the YAML header, include:
```
output: 
  pdf_document:
    citation_package: natbib
    keep_tex: true
    fig_caption: true
    latex_engine: pdflatex
    template: ~/path/to/template.tex
```