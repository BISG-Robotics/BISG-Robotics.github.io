---
title: "Filling Missing Values Matters for Range Image-Based Point Cloud Segmentation"

# Warning: for the authors in this website, use the names matching the folders, making sure tha the name can link to your personal page. For the authors not in this website, use the true names. 
authors:
- Bike_Chen
- Chen Gong
- Juha_Roning
author_notes:
- ""
- ""
date: "2024-08-19T00:00:00Z"
doi: "10.1109/TIV.2024.3445814"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-19T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Intelligent Vehicles (IEEE TIV)* (JUFO Level 2)"
publication_short: ""

abstract: Point cloud segmentation (PCS) plays an essential role in robot perception and navigation tasks. To efficiently understand large-scale outdoor point clouds, their range image representation is commonly adopted. This image-like representation is compact and structured, making range image-based PCS models practical. However, undesirable missing values in the range images damage the shapes and patterns of objects. This problem creates difficulty for the models in learning coherent and complete geometric information from the objects. Consequently, the PCS models only achieve inferior performance. Delving deeply into this issue, we find that the use of unreasonable projection approaches and deskewing scans mainly leads to unwanted missing values in the range images. Besides, almost all previous works fail to consider filling in the unexpected missing values in the PCS task. To alleviate this problem, we first propose a new projection method, namely scan unfolding++ (SU++), to avoid massive missing values in the generated range images. Then, we introduce a simple yet effective approach, namely range-dependent $K$-nearest neighbor interpolation ($K$NNI), to further fill in missing values. Finally, we introduce the Filling Missing Values Network (FMVNet) and Fast FMVNet. Extensive experimental results on SemanticKITTI, SemanticPOSS, and nuScenes datasets demonstrate that by employing the proposed SU++ and $K$NNI, existing range image-based PCS models consistently achieve better performance than the baseline models. Besides, both FMVNet and Fast FMVNet achieve state-of-the-art performance in terms of the speed-accuracy trade-off. The proposed methods can be applied to other range image-based tasks and practical applications.

# Summary. An optional shortened abstract.
summary: A novel method for range image-based point cloud segmentation.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "https://ieeexplore.ieee.org/document/10638804" 
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
