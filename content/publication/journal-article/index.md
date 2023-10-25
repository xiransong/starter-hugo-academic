---
title: "Temporal Heterogeneous Information Network Embedding via Semantic Evolution"
authors:
- Wei Zhou
- Hong Huang
- Ruize Shi
- Xiran Song
- Xue Lin
- Xiao Wang
- Hai Jin
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Knowledge and Data Engineering"
publication_short: "TKDE'23"

# abstract: ''

# # Summary. An optional shortened abstract.
# summary: ''

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://doi.ieeecomputersociety.org/10.1109/TKDE.2023.3287260'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects: []

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).-->


**Abstract:**

Real-world networks are often heterogeneous and constantly changing over time. Evolution reveals the trend of network development, which is vital for predicting its future state, and network embedding can effectively learn the information from it. Nevertheless, previous works only consider the impact of meta-path instances or node neighbors on the network dynamics but ignore the relationship between them, and hence the hidden semantic information is missed, which will result in performance deterioration. Therefore, we propose a novel temporal heterogeneous information network embedding method (SemE), which abstracts the instance of the meta-path as semantic units and then considers the interaction between them to discover deeper semantic information. Specifically, we first construct semantic networks by the Ethernet topology and the interaction between semantic units. The semantic units are sampled based on a pre-designed meta-path-guided random walk. To further capture the semantic evolution of the semantic network, we learn the embedding of nodes by the attention-Hawkes process. Finally, we generate the final embedding by aggregating the structure, semantic and temporal information with the attention mechanism. Experiments on three real-world temporal heterogeneous information networks show that our model performs better than competitive counterparts.
