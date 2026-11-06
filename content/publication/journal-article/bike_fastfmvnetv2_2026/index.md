---
title: "Trainable Pointwise Decoder Module and Virtual Range Image-Guided Copy-Rotate-Paste Augmentation for Point Cloud Segmentation"

# Warning: for the authors in this website, use the names matching the folders, making sure tha the name can link to your personal page. For the authors not in this website, use the true names. 
authors:
- Bike_Chen
- Chen Gong
- Antti_Tikanmaki
- Juha_Roning
author_notes:
- ""
- ""
date: "2026-08-01T00:00:00Z"
doi: "10.1016/j.cviu.2026.104859"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-08-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Computer Vision and Image Understanding (CVIU)* (JUFO Level 2)"
publication_short: ""

abstract: Point cloud segmentation (PCS) aims to make per-point predictions, enabling robots and autonomous driving cars to understand their environments. The range image is a dense representation of a large-scale outdoor point cloud. Segmentation models built upon the range image commonly execute efficiently. However, the projection of the point cloud onto the range image inevitably leads to dropping points because multiple points could be projected onto the same image location, but only one point is kept. More importantly, it is challenging to assign correct predictions to the dropped points with different classes from the kept point class. Besides, existing post-processing methods, such as $K$-nearest neighbor ($K$NN) search and kernel point convolution (KPConv), cannot be trained with the models in an end-to-end manner or cannot process varying-density outdoor point clouds well, thereby enabling the models to achieve sub-optimal performance. To alleviate this problem, we propose a trainable pointwise decoder module (PDM) as the post-processing approach, which gathers weighted features from the neighbors and then makes the final prediction for the query point. In addition, we introduce a virtual range image-guided copy-rotate-paste (VRCrop) strategy in data augmentation. VRCrop constrains the total number of points and eliminates undesirable artifacts in the augmented point cloud. Also, VRCrop is model-agnostic and can be easily employed in various PCS models. With PDM and VRCrop, existing range image-based segmentation models consistently surpass their counterparts on the SemanticKITTI, SemanticPOSS, and nuScenes datasets.

# Summary. An optional shortened abstract.
summary: A novel method for range image-based point cloud segmentation.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "https://www.sciencedirect.com/science/article/pii/S1077314226002262" 
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
