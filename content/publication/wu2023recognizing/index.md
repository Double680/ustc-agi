---
title: 'Recognizing unseen objects via multimodal intensive knowledge graph propagation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Likang Wu
  - Zhi Li
  - Hongke Zhao
  - Zhefeng Wang
  - Qi Liu
  - Baoxing Huai
  - Nicholas Jing Yuan
  - Enhong Chen

# Author notes (optional)
# author_notes:
date: '2024-08-04'
doi: '10.1145/3580305.3599486'

# Schedule page publish date (NOT publication's date).
# publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining*
publication_short: In *KDD*

abstract: Zero-Shot Learning (ZSL), which aims at automatically recognizing unseen objects, is a promising learning paradigm to understand new real-world knowledge for machines continuously. Recently, the Knowledge Graph (KG) has been proven as an effective scheme for handling the zero-shot task with large-scale and non-attribute data. Prior studies always embed relationships of seen and unseen objects into visual information from existing knowledge graphs to promote the cognitive ability of the unseen data. Actually, real-world knowledge is naturally formed by multimodal facts. Compared with ordinary structural knowledge from a graph perspective, multimodal KG can provide cognitive systems with fine-grained knowledge. For example, the text description and visual content can depict more critical details of a fact than only depending on knowledge triplets. Unfortunately, this multimodal fine-grained knowledge is largely unexploited due to the bottleneck of feature alignment between different modalities. To that end, we propose a multimodal intensive ZSL framework that matches regions of images with corresponding semantic embeddings via a designed dense attention module and self-calibration loss. It makes the semantic transfer process of our ZSL framework learns more differentiated knowledge between entities. Our model also gets rid of the performance limitation of only using rough global features. We conduct extensive experiments and evaluate our model on large-scale real-world data. The experimental results clearly demonstrate the effectiveness of the proposed model in standard zero-shot classification tasks.

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
