---
title: 'GraphInstruct: Empowering Large Language Models with Graph Understanding and Reasoning Capability'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zihan Luo
  - Xiran Song
  - Hong Huang
  - Jianxun Lian
  - Chenhao Zhang
  - Jinqi Jiang
  - Xing Xie

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - ''
#   - 'Equal contribution'

date: ''
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['']

# Publication name and optional abbreviated publication name.
publication: 'arXiv'
publication_short: 'arXiv'

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

url_pdf: '/files/GraphInstruct.pdf'
url_code: 'https://github.com/CGCL-codes/GraphInstruct'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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

Evaluating and enhancing the general capabilities of large language models (LLMs) has
been an important research topic. Graph is
a common data structure in the real world,
and understanding graph data is a crucial part
for advancing general intelligence. To evaluate and enhance the graph understanding abilities of LLMs, in this paper, we propose a
benchmark named GraphInstruct, which comprehensively includes 21 classical graph reasoning tasks, providing diverse graph generation pipelines and detailed reasoning steps.
Based on GraphInstruct, we further construct
GraphLM through efficient instruction-tuning,
which shows prominent graph understanding
capability. In order to enhance the LLM with
graph reasoning capability as well, we propose
a step mask training strategy, and construct a
model named GraphLM+. As one of the pioneering efforts to enhance the graph understanding and reasoning abilities of LLMs, extensive
experiments have demonstrated the superiority
of GraphLM and GraphLM+ over other LLMs.
We look forward to more researchers exploring
the potential of LLMs in the graph data mining domain through GraphInstruct. Our code
for generating GraphInstruct is released publicly at: https://github.com/CGCL-codes/GraphInstruct.
