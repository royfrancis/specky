# specky

[![ci_badge](https://github.com/royfrancis/specky/workflows/deploy/badge.svg)](https://github.com/royfrancis/specky/actions?workflow=deploy)  [![linkcheck_badge](https://github.com/royfrancis/specky/workflows/linkcheck/badge.svg)](https://github.com/royfrancis/specky/actions?workflow=linkcheck)  [![lifecycle_badge](https://lifecycle.r-lib.org/articles/figures/lifecycle-experimental.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)

Quarto website template for courses

![Report home](preview-home.webp)

![Report preview](preview-report.webp)

![Slide preview](preview-slide.webp)

For a demo site and usage, see [here](https://royfrancis.github.io/specky).

## Usage

- Recommended quarto 1.6.43 or higher
- To download and use a starter template, run in the terminal

:exclamation: Demo files are not downloaded

```
quarto use template royfrancis/specky
```

- Install required extensions

```
quarto add --no-prompt quarto-ext/fontawesome
quarto add --no-prompt royfrancis/quarto-revealjs-header
quarto add --no-prompt royfrancis/quarto-revealjs-pointer
quarto add --no-prompt mcanouil/quarto-collapse-output@1.4.0
quarto add --no-prompt royfrancis/quarto-accordion
quarto add --no-prompt royfrancis/quarto-leaflet
```

- Render all html files into `docs` directory to make sure everything works as expected

```
quarto render
```

- See more documentation on the [demo site](https://royfrancis.github.io/specky/home_contents.html) for customization

## Showcase

Here are a few examples of this template in action:

- [Introduction to Bioinformatics using NGS data](https://nbisweden.github.io/workshop-ngsintro/2511/)
- [Single-cell RNA-seq analysis](https://nbisweden.github.io/workshop-scRNAseq/)
- [Tools for reproducible research](https://nbisweden.github.io/workshop-reproducible-research/)
- [Advanced data visualization](https://nbisweden.github.io/workshop-data-visualization-r/2505/)

## Acknowledgements

- Built using [Quarto](https://quarto.org/)
- Uses the [fontawesome extension](https://github.com/quarto-ext/fontawesome) for icons
- Uses the [collapse-output extension](mcanouil/quarto-collapse-output@1.4.0) for code output folding

---

2026 • Roy Francis
