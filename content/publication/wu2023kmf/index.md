---
title: 'KMF: knowledge-aware multi-faceted representation learning for zero-shot node classification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Likang Wu
  - Junji Jiang
  - Hongke Zhao
  - Hao Wang
  - Defu Lian
  - Mingdi Zhang
  - Enhong Chen

# Author notes (optional)
# author_notes:
date: '2023-08-19'
doi: '10.24963/ijcai.2023/262'

# Schedule page publish date (NOT publication's date).
# publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the Thirty-Second International Joint Conference on Artificial Intelligence*
publication_short: In *IJCAI*

abstract: Recently, Zero-Shot Node Classification (ZNC) has been an emerging and crucial task in graph data analysis. This task aims to predict nodes from unseen classes which are unobserved in the training process. Existing work mainly utilizes Graph Neural Networks (GNNs) to associate features' prototypes and labels' semantics thus enabling knowledge transfer from seen to unseen classes. However, the multi-faceted semantic orientation in the feature-semantic alignment has been neglected by previous work, i.e. the content of a node usually covers diverse topics that are relevant to the semantics of multiple labels. It's necessary to separate and judge the semantic factors that tremendously affect the cognitive ability to improve the generality of models. To this end, we propose a Knowledge-Aware Multi-Faceted framework (KMF) that enhances the richness of label semantics via the extracted KG (Knowledge Graph)-based topics. And then the content of each node is reconstructed to a topic-level representation that offers multi-faceted and fine-grained semantic relevancy to different labels. Due to the particularity of the graph's instance (i.e., node) representation, a novel geometric constraint is developed to alleviate the problem of prototype drift caused by node information aggregation. Finally, we conduct extensive experiments on several public graph datasets and design an application of zero-shot cross-domain recommendation. The quantitative results demonstrate both the effectiveness and generalization of KMF with the comparison of state-of-the-art baselines.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
