---
title: "Supporting Your Idea Reasonably: A Knowledge-Aware Topic Reasoning Strategy for Citation Recommendation"
authors:
- Likang Wu
- Zhi Li
- Hongke Zhao
- Zhenya Huang
- Yongqiang Han
- Junji Jiang
- Enhong Chen

# author_notes:
date: "2024-02-22"
doi: "10.1109/TKDE.2024.3365508"

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Knowledge and Data Engineering"
publication_short: "IEEE TKDE"

abstract: With the explosive growth of scholarly information, researchers spend much time and effort copiously quoting authoritative works to support their ideas or motivations. We aim to alleviate this situation by proposing a citation recommendation strategy that recalls related papers for a rough idea (a piece of text, i.e., abstract, manuscript). However, the perspective of existing citation recommendations can not be well applied to our task for two defects. First, these methods neglect the reasoning of research topics, which makes the recommendation mechanism not meticulous enough and lacks explainability. For instance, they are not able to mine the hidden citing logic for the candidate paper while recommending. We fill the research gap by constructing structural topics consisting of knowledge concepts from the textual content, where reasoning paths between topics are extracted from an external knowledge graph. Second, the citation network is viewed as a crucial structural context to enhance the recommendation performance, but the new target idea does not have links to the citation network as published papers do. To simulate the prospective topological structure, our model, meanwhile, incorporates a contrastive-learning-based alignment paradigm to encourage the consistency of content embeddings and structure-oriented embeddings. We evaluate our proposed model on three real-world datasets and demonstrate that it significantly improves recommendation accuracy while providing high-quality knowledge-aware reasoning. And an interesting visual example illustrates the reasoning process when our model actually judges samples, which supports the feasibility of our topic-view learning paradigm.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []
featured: false

# links:
# - name: ""
#   url: ""
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
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
