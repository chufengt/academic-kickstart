---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Improving Pedestrian Attribute Recognition With Weakly-Supervised Multi-Scale Attribute-Specific Localization"
authors: ["[**Chufeng Tang**](https://chufengt.github.io)", "[Lu Sheng](https://lucassheng.github.io)", "[Zhaoxiang Zhang](https://zhaoxiangzhang.net/)", "[Xiaolin Hu](http://xlhu.cn)<sup>*"]
date: 2019-10-10T23:43:23+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-10-10T23:43:23+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The IEEE International Conference on Computer Vision (**ICCV**), 2019"
publication_short: "ICCV 2019"

abstract: "Pedestrian attribute recognition has been an emerging research topic in the area of video surveillance. To predict the existence of a particular attribute, it is demanded to localize the regions related to the attribute. However, in this task, the region annotations are not available. How to carve out these attribute-related regions remains challenging. Existing methods applied attribute-agnostic visual attention or heuristic body-part localization mechanisms to enhance the local feature representations, while neglecting to employ attributes to define local feature areas. We propose a flexible Attribute Localization Module (ALM) to adaptively discover the most discriminative regions and learns the regional features for each attribute at multiple levels. Moreover, a feature pyramid architecture is also introduced to enhance the attribute-specific localization at low-levels with high-level semantic guidance. The proposed framework does not require additional region annotations and can be trained end-to-end with multi-level deep supervision. Extensive experiments show that the proposed method achieves state-of-the-art results on three pedestrian attribute datasets, including PETA, RAP, and PA-100K."

# Summary. An optional shortened abstract.
summary: "The IEEE International Conference on Computer Vision (**ICCV**), 2019"

tags: [Deep Learning, Computer Vision, Pedestrian Attribute Recognition]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter
links:
  - name: Supplementary
    url: "http://openaccess.thecvf.com/content_ICCV_2019/supplemental/Tang_Improving_Pedestrian_Attribute_ICCV_2019_supplemental.pdf"
  - name: ArXiv
    url: "https://arxiv.org/abs/1910.04562"

url_pdf: "http://openaccess.thecvf.com/content_ICCV_2019/papers/Tang_Improving_Pedestrian_Attribute_Recognition_With_Weakly-Supervised_Multi-Scale_Attribute-Specific_Localization_ICCV_2019_paper.pdf"
url_code: "https://github.com/chufengt/iccv19_attribute"
url_dataset:
url_poster: "iccv_poster_id2029.pdf"
url_project:
url_slides:
url_source:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
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
slides: ""
---
