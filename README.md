# R/Pharma GenAI Day 2026 Artifacts

Resources for the talk **"Ignore All Previous Instructions" and Other Things Your LLM Shouldn't Do in Pharma: Applying GenAI Security Guardrails in R**.

This repository contains the talk notebook, a rendered notebook, and a compact GitHub Pages landing page for the supporting links and artifacts.

## Open The Site

- Landing page: [`index.html`](index.html)
- Rendered notebook: [`genaiday.html`](genaiday.html)
- Notebook source: [`genaiday.ipynb`](genaiday.ipynb)

If this repository is published with GitHub Pages, `index.html` is the default page.

## What Is Included

| File | Purpose |
|---|---|
| [`index.html`](index.html) | One-page no-scroll resource page for GitHub Pages |
| [`genaiday.html`](genaiday.html) | Rendered version of the notebook |
| [`genaiday.ipynb`](genaiday.ipynb) | Source notebook for the demo |
| [`renv.lock`](renv.lock) | R package environment lockfile |
| [`renv/activate.R`](renv/activate.R) | renv project activation script |

## Main Resources

- [`{llmshieldr}` on CRAN](https://cloud.r-project.org/web/packages/llmshieldr/index.html)
- [`{llmshieldr}` reference manual PDF](https://cran.r-project.org/web/packages/llmshieldr/llmshieldr.pdf)
- [`{llmshieldr}` documentation site](https://www.indraneelchakraborty.com/llmshieldr/)
- [`{llmshieldr}` GitHub repository](https://github.com/ineelhere/llmshieldr)
- [OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/)
- [`{ellmer}` on CRAN](https://cran.r-project.org/package=ellmer)
- [Ollama](https://ollama.com/)
- [R/Pharma GenAI Day](https://rinpharma.com/docs/ai-day/)

## Reproduce The Notebook

Open the project in R/RStudio and restore the package environment:

```r
renv::restore()
```

The notebook examples expect Ollama to be installed and running locally for cells that create chat or reviewer objects.

## Notes

Generated local logs, caches, checkpoints, and local package libraries are ignored via `.gitignore`. The committed files are intended to be enough for reading the talk materials and rebuilding the R environment.

