---
title: "Hyperbolic Uncertainty Aware Semantic Segmentation"

# Warning: for the authors in this website, use the names matching the folders, making sure tha the name can link to your personal page. For the authors not in this website, use the true names. 
authors:
- Bike_Chen
- Wei Peng
- Xiaofeng Cao
- Juha_Roning
author_notes:
- ""
- ""
date: "2023-09-18T00:00:00Z"
doi: "10.1109/TITS.2023.3312290"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Intelligent Transportation Systems (IEEE T-ITS)* (JUFO Level 2)"
publication_short: ""

abstract: Semantic segmentation (SS) aims to classify each pixel into one of the pre-defined classes. This task plays an important role in self-driving cars and autonomous drones. In SS, many works have shown that most misclassified pixels are commonly near object boundaries with high uncertainties. However, existing SS loss functions are not tailored to handle these uncertain pixels during training, as these pixels are usually treated equally as confidently classified pixels and cannot be embedded with arbitrary low distortion in Euclidean space, thereby degenerating the performance of SS. To overcome this problem, this paper designs a Hyperbolic Uncertainty Loss (HyperUL), which dynamically highlights the misclassified and high-uncertainty pixels in Hyperbolic space during training via the hyperbolic distances. The proposed HyperUL is model agnostic and can be easily applied to various neural architectures. After employing HyperUL to three recent SS models, the experimental results on Cityscapes, UAVid, and ACDC datasets reveal that the segmentation performance of existing SS models can be consistently improved. Additionally, reliable measurement of model uncertainty plays a key role in real-world applications such as autonomous controls of vehicles and drones. To meet this requirement, we propose the Hyperbolic Uncertainty Estimation method, which is easily implemented by only post-processing the generated Hyperbolic embeddings. By this approach, we can calculate the uncertainty values almost for free. Quantitative and qualitative results on Cityscapes, UAVid, and ACDC datasets verify that our proposed uncertainty estimation method usually outputs more meaningful results compared with popular MC-dropout and ensembling methods.

# Summary. An optional shortened abstract.
summary: We apply Hyperbolic space in semantic image segmentation.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10254452" 
# url_code: '' # 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: '' # 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- {{% callout note %}}
Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
{{% /callout %}} -->
