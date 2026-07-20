---
title: 'MIBench: Evaluating LMMs on Multimodal Interaction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yu Miao*
  - Zequn Yang*
  - Yake Wei
  - Ziheng Chen
  - admin
  - Haodong Duan
  - Kai Chen
  - Di Hu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-03-13T03:02:24Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-03-13T03:02:24Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: arXiv preprint arXiv:2603.13427
publication_short: arXiv 2026

abstract: |
  In different multimodal scenarios, it needs to integrate and utilize information across modalities in a specific way based on the demands of the task. Different integration ways between modalities are referred to as "multimodal interaction". How well a model handles various multimodal interactions largely characterizes its multimodal ability. In this paper, we introduce MIBench, a comprehensive benchmark designed to evaluate the multimodal interaction capabilities of Large Multimodal Models (LMMs), which formulates each instance as a (con_v, con_t, task) triplet with contexts from vision and text, necessitating that LMMs employ correct forms of multimodal interaction to effectively complete the task. MIBench assesses models from three key aspects: the ability to source information from vision-centric or text-centric cues, and the ability to generate new information from their joint synergy. Each interaction capability is evaluated hierarchically across three cognitive levels: Recognition, Understanding, and Reasoning. MIBench comprises over 10,000 vision-text context pairs spanning 32 distinct tasks. Evaluation of state-of-the-art LMMs show that: (1) LMMs' ability on multimodal interaction remains constrained, despite the scaling of model parameters and training data; (2) they are easily distracted by textual modalities when processing vision information; (3) they mostly possess a basic capacity for multimodal synergy; and (4) natively trained multimodal models show noticeable deficits in fundamental interaction ability. We expect that these observations can serve as a reference for developing LMMs with more enhanced multimodal ability in the future.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Multimodal Learning
  - Large Multimodal Models
  - Benchmark

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2603.13427'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
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
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

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
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

