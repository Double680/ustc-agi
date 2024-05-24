---
title: 'Exploring large language model for graph data understanding in online job recommendations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Likang Wu
  - Zhaopeng Qiu
  - Zhi Zheng
  - Hengshu Zhu
  - Enhong Chen

# Author notes (optional)
# author_notes:
date: '2024-03-24'
doi: '10.1609/aaai.v38i8.28769'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-24'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the AAAI Conference on Artificial Intelligence*
publication_short: In *AAAI*

abstract: Large Language Models (LLMs) have revolutionized natural language processing tasks, demonstrating their exceptional capabilities in various domains. However, their potential for graph semantic mining in job recommendations remains largely unexplored. This paper focuses on unveiling the capability of large language models in understanding behavior graphs and leveraging this understanding to enhance recommendations in online recruitment, including promoting out-of-distribution (OOD) applications. We present a novel framework that harnesses the rich contextual information and semantic representations provided by large language models to analyze behavior graphs and uncover underlying patterns and relationships. Specifically, we propose a meta-path prompt constructor that aids LLM recommender in grasping the semantics of behavior graphs for the first time and design a corresponding path augmentation module to alleviate the prompt bias introduced by path-based sequence input. By facilitating this capability, our framework enables personalized and accurate job recommendations for individual users. We evaluate the effectiveness of our approach on comprehensive real-world datasets and demonstrate its ability to improve the relevance and quality of recommended results. This research not only sheds light on the untapped potential of large language models but also provides valuable insights for developing advanced recommendation systems in the recruitment market. The findings contribute to the growing field of natural language processing and offer practical implications for enhancing job search experiences.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

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
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
