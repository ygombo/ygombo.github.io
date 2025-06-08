---
title: "Communication-Free Decentralized Controller Design for Flexible Object Transport"
authors:
- Yoshua Gombo
- Anuj Tiwari
- Mohamed Safwat
- Henry Chang
- Santosh Devasia
author_notes:
date: "2015-09-01T00:00:00Z"
doi: "https://doi.org/10.1109/TMECH.2024.3399120"

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

tags:
- Networked robots

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



{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
