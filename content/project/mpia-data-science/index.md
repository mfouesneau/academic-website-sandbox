---
title: Arxiv on Deck
summary: A not so simpler Arxiver
tags:
- Arxiv
- papers
- mpia tool
date: "2022-03-28T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: "https://mfouesneau.github.io/arxiv_on_deck_2/"

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
url_code: "https://mfouesneau.github.io/arxiv_on_deck_2/"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

{{% callout note %}}
[Arxiv on deck 2](https://mfouesneau.github.io/arxiv_on_deck_2/)
{{% /callout %}}



This project is a python package, the next version of [arxiv_on_deck](https://github.com/mfouesneau/arxiv_on_deck), a quick and dirty version of the [Arxiver](https://arxiver.moonhats.com/).

The main goal of this package is to find papers authored by a given list of authors (e.g., a list of institute members) and only for those compiles a 1 page summary with figures (and captions).

It is a sort of Arxiver for institutes or groups

This evolution initially uses arXiv Vanity that renders academic papers from arXiv as responsive web pages. This package cannot entirely rely on arXiv Vanity to render the documents correctly, and it is often having issues or incorrect rendering. Hence, it also implements latex parsing methods to extract information.

This package searches for new articles on ArXiv and renders their summary as Markdown documents. It does not compile the original LaTeX documents and only extracts the relevant information.