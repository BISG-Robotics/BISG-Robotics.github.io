---
title: "Depth-Aware Range Image-Based Model for Point Cloud Segmentation"
authors:
- Bike_Chen
- Antti_Tikanmaki
- Juha_Roning
date: "2025-05-19T00:00:00Z"
doi: "https://arxiv.org/abs/2503.14955"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-19T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv"
publication_short: ""

abstract: Point cloud segmentation (PCS) aims to separate points into different and meaningful groups. The task plays an important role in robotics because PCS enables robots to understand their physical environments directly. To process sparse and large-scale outdoor point clouds in real time, range image-based models are commonly adopted. However, in a range image, the lack of explicit depth information inevitably causes some separate objects in 3D space to touch each other, bringing difficulty for the range image-based models in correctly segmenting the objects. Moreover, previous PCS models are usually derived from the existing color image-based models and unable to make full use of the implicit but ordered depth information inherent in the range image, thereby achieving inferior performance. In this paper, we propose Depth-Aware Module (DAM) and Fast FMVNet V3. DAM perceives the ordered depth information in the range image by explicitly modelling the interdependence among channels. Fast FMVNet V3 incorporates DAM by integrating it into the last block in each architecture stage. Extensive experiments conducted on SemanticKITTI, nuScenes, and SemanticPOSS demonstrate that DAM brings a significant improvement for Fast FMVNet V3 with negligible computational cost.

# Summary. An optional shortened abstract.
summary: A novel point cloud segmentation module is proposed.

tags:
- Source Themes
featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2503.14955
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "" #'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
