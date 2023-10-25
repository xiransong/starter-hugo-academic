---
title: 'Friend Recommendations with Self-Rescaling Graph Neural Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xiran Song
  - Jianxun Lian
  - Hong Huang
  - Mingqi Wu
  - Hai Jin
  - Xing Xie

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - ''
#   - 'Equal contribution'

date: '2022-08-14T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-08-14T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining*
publication_short: In *KDD'22*

# abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3534678.3539192'
url_code: 'https://github.com/CGCL-codes/ssnet'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://dl.acm.org/doi/10.1145/3534678.3539192#sec-supp'

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
#   - example

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->

**Abstract:**

Friend recommendation service plays an important role in shaping and facilitating the growth of online social networks. Graph embedding models, which can learn low-dimensional embeddings for nodes in the social graph to effectively represent the proximity between nodes, have been widely adopted for friend recommendations. Recently, Graph Neural Networks (GNNs) have demonstrated superiority over shallow graph embedding methods, thanks to their ability to explicitly encode neighborhood context. This is also verified in our Xbox friend recommendation scenario, where some simplified GNNs, such as LightGCN and PPRGo, achieve the best performance. However, we observe that many GNN variants, including LightGCN and PPRGo, use a static and pre-defined normalizer in neighborhood aggregation, which is decoupled with the representation learning process and can cause the scale distortion issue. As a consequence, the true power of GNNs has not yet been fully demonstrated in friend recommendations.

In this paper, we propose a simple but effective self-rescaling network (SSNet) to alleviate the scale distortion issue. At the core of SSNet is a generalized self-rescaling mechanism, which bridges the neighborhood aggregator's normalization with the node embedding learning process in an end-to-end framework. Meanwhile, we provide some theoretical analysis to help us understand the benefit of SSNet. We conduct extensive offline experiments on three large-scale real-world datasets. Results demonstrate that our proposed method can significantly improve the accuracy of various GNNs. When deployed online for one month's A/B test, our method achieves 24% uplift in adding suggested friends actions. At last, we share some interesting findings and hope the experience can motivate future applications and research in social link predictions.
