---
title: "Communication-Free Decentralized Controller Design for Flexible Object Transport"
authors:
- Yoshua Gombo
- Anuj Tiwari
- Mohamed Safwat
- Henry Chang
- Santosh Devasia
author_notes:
date: "2024-06-04T00:00:00Z"
doi: "10.1109/TMECH.2024.3399120"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-04T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ASME Transactions on Mechatronics"
publication_short: "IEEE/ASME T-MECH"

abstract: Bio-inspired decentralized approaches for transporting objects with robot networks seek to use locally-sensed information such as object–robot interaction forces, without the need for robot-to-robot communication. However, the design of the decentralized controller to achieve a specified network performance (e.g., to achieve a desired network settling time Ts) depends on the particular network/object connectivity and therefore, tends to be a centralized decision. Such centralized controller design is not biomimetic and might not be viable if communication is not available between agents to achieve decentralized consensus on the controller parameters. The main contribution of this article is a decentralized controller design approach using local measurements, which does not require prior knowledge of the robot network or object properties. Rather, only the desired network-level performance (such as network settling time) is needed to select controller parameters with the proposed delayed self-reinforcement (DSR) approach, which decentralizes the ideal case where each robot has information about the transport task. In addition, experimental results show that the DSR approach (with decentralized parameter selection) reduces deformation substantially by 66% for a linear object using mobile robots and by 57% for the planar transport of a cylindrical object using industrial robots, when compared to the standard (without DSR) case, even with a centralized design of parameters.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Networked robots
tags: ["Networked robots"]
categories: ["journal"]

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/10547233
url_code: 
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=dX5XPI-zhuo&t=1s'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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

A decentralized way to choose controller parameters for robot teams transporting objects, using only local measurements and the desired network performance, with no prior knowledge of the network or object. Experiments show the DSR approach reduces deformation by 66% with mobile robots and 57% with industrial robots.
