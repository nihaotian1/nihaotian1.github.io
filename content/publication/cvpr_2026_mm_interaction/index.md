---
title: 'Information-Theoretic Decomposition for Multimodal Interaction Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zequn Yang
  - Yake Wei
  - admin
  - Zhihao Xu
  - Di Hu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-03-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-03-03T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Computer Vision and Pattern Recognition 2026*
publication_short: In *CVPR 2026*

abstract: Multimodal learning hinges on capturing redundant, unique,and synergistic information across modalities, which collectively constitute multimodal interactions. A critical yet underexplored challenge is that these implicit interactions vary dynamically across samples. In this work, we present the first systematic, information-theoretic analysis highlighting why learning these dynamic, sample-specific interactions is critical for effective multimodal learning. Our analysis further reveals deficits in conventional paradigms at learning these distinct interaction types: modality ensemble approaches struggle to capture synergy, while joint learning paradigms often under-utilize redundant information. This highlightsthe need for an approach that can adaptively learn from different interaction types on a per-sample basis. To this end, we propose Decomposition-based Multimodal Interaction Learning (DMIL), a novel paradigm that explicitly models and learns from sample-specific interactions. First, we design a variational decomposition architecture to isolate the constituent interaction components. Second, we employ a new learning strategy that leverages these explicit interaction components in a fine-tuning process to achieve comprehensive interaction learning. Extensive experiments across diverse tasks and architectures demonstrate that DMIL consistently achieves superior performance by adapting to holistic sample-specific interactions. Our framework is flexible and broadly applicable, establishing an interaction-centric paradigm for multimodal learning.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Multimodal Learning

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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



