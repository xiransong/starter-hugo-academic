---
title: 'xGCN: An Extreme Graph Convolutional Network for Large-scale Social Link Prediction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xiran Song
  - Jianxun Lian
  - Hong Huang
  - Zihan Luo
  - Wei Zhou
  - Xue Lin
  - Mingqi Wu
  - Chaozhuo Li
  - Xing Xie
  - Hai Jin

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - ''
#   - 'Equal contribution'

date: '2023-04-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The ACM Web Conference 2023*
publication_short: In *WWW'23*

# abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3543507.3583340'
url_code: 'https://github.com/CGCL-codes/xGCN'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=8yedOmd_3Fw'

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

Graph neural networks (GNNs) have seen widespread usage across multiple real-world applications, yet in transductive learning, they still face challenges in accuracy, efficiency, and scalability, due to the extensive number of trainable parameters in the embedding table and the paradigm of stacking neighborhood aggregations. This paper presents a novel model called xGCN for large-scale network embedding, which is a practical solution for link predictions. xGCN addresses these issues by encoding graph-structure data in an extreme convolutional manner, and has the potential to push the performance of network embedding-based link predictions to a new record. Specifically, instead of assigning each node with a directly learnable embedding vector, xGCN regards node embeddings as static features. It uses a propagation operation to smooth node embeddings and relies on a Refinement neural Network (RefNet) to transform the coarse embeddings derived from the unsupervised propagation into new ones that optimize a training objective. The output of RefNet, which are well-refined embeddings, will replace the original node embeddings. This process is repeated iteratively until the model converges to a satisfying status. Experiments on three social network datasets with link prediction tasks show that xGCN not only achieves the best accuracy compared with a series of competitive baselines but also is highly efficient and scalable.
