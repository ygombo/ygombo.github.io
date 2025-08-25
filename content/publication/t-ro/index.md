---
title: 'Delayed Self-Reinforcement to Reduce Deformation During Decentralized Flexible-Object Transport'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yoshua Gombo
  - Anuj Tiwari
  - Mohamed Safwat
  - Henry Chang
  - Santosh Devasia

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-12-01T00:00:00Z'
doi: '10.1109/TRO.2023.3343997'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Robotics*
publication_short: In *IEEE T-RO*

abstract: Recent works have investigated bio-inspired strategies to transport objects using decentralized robot networks that only use local measurements without the need for communication between robots. Typically, there is an inverse relationship between the object deformation and the transport time, i.e., reducing the object deformation requires an increase in the transport time needed for transitioning from the initial configuration to the final configuration of the object. In contrast, the main contribution in this article is the development of a delayed self-reinforcement (DSR) approach that seeks to decentralize the ideal centralized transport that has no object deformation, and thereby, reduces the object deformation without increasing the transport time for the same specified transport trajectory. In the DSR method, each robot only uses already available prior-information to reinforce each robot's actions, and thus, the DSR implementation does not require additional information or changes in the network structure. Another contribution in this article is to analyze the potentially time-varying dynamics to establish conditions on the control parameters for stability and quantify the performance of the proposed DSR-based transport. Furthermore, experimental results are presented to show that the proposed cohesive transport method can reduce the deformation by at least 72% for the same transport time, when compared with the case without DSR.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
#   - Networked robots
tags: ["Networked robots"]
categories: ["journal"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10363675'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=sGCo6Woei3Q'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
