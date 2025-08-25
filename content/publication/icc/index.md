---
title: "Improving network's transition cohesion by approximating strongly damped waves using delayed self reinforcement"
authors:
- Anuj Tiwari
- Yoshua Gombo
- Santosh Devasia
date: "2021-12-20T00:00:00Z"
doi: "10.1109/ICC54714.2021.9703122"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Indian Control Conference"
publication_short: "2021 ICC"

abstract: Cohesive networks aim to achieve similar response in each agent not only at steady state but also during transitions from one consensus value to another. Standard consensus-based approaches approximate the diffusion equation, which leads to decay of transition information for agents that are farther away from the leader, and results in loss of cohesion during rapid changes. Increasing the alignment strength in standard first-order consensus-based approaches enables each agent to respond faster to the changes in neighbor states. Nevertheless, it does not necessarily increase cohesion during the transition. Moreover, increasing the alignment strength also requires an increase in update bandwidth. In contrast, delayed self reinforcement (DSR) approach enables increased cohesion without increasing the update bandwidth. The main contribution of this article is to explain this increased cohesion with DSR by showing that the DSR approximates a strongly damped wave equation, where each agent not only attempts to align with its neighboring states but also to align with the rate of change of its neighboring states.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Networked robots
tags: ["Networked robots"]
categories: ["article"]

featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://ieeexplore.ieee.org/abstract/document/9703122
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
