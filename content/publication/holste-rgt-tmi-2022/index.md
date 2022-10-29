---
title: "Radiomics-Guided Global-Local Transformer for Weakly Supervised Pathology Localization in Chest X-Rays"
authors:
- Yan Han
- Gregory Holste
- Ying Ding
- Ahmed Tewfik
- Yifan Peng
- Zhangyang Wang
date: "2022-10-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Medical Imaging"
publication_short: "IEEE TMI"

abstract: 'Before the recent success of deep learning methods for automated medical image analysis, practitioners used handcrafted radiomic features to quantitatively describe local patches of medical images. However, extracting discriminative radiomic features relies on accurate pathology localization, which is difficult to acquire in real-world settings. Despite advances in disease classification and localization from chest X-rays, many approaches fail to incorporate clinically-informed domain knowledge. For these reasons, we propose a Radiomics-Guided Transformer (RGT) that fuses global image information with local knowledge-guided radiomics information to provide accurate cardiopulmonary pathology localization and classification without any bounding box annotations. RGT consists of an image Transformer branch, a radiomics Transformer branch, and fusion layers that aggregate image and radiomic information. Using the learned self-attention of its image branch, RGT extracts a bounding box for which to compute radiomic features, which are further processed by the radiomics branch; learned image and radiomic features are then fused and mutually interact via cross-attention layers. Thus, RGT utilizes a novel end-to-end feedback loop that can bootstrap accurate pathology localization only using image-level disease labels. Experiments on the NIH ChestXRay dataset demonstrate that RGT outperforms prior works in weakly supervised disease localization (by an average margin of 3.6% over various intersection-over-union thresholds) and classification (by 1.1% in average area under the receiver operating characteristic curve). We publicly release our codes and pre-trained models at https://github.com/VITA-Group/chext.'

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#3C94B5">IEEE Transactions on Medical Imaging</b><br> A Transformer for weakly supervised disease localization that uses a novel feedback loop between (local) radiomics features and (global) chest X-ray features.

tags:
- Source Themes
featured: true

url_pdf: 'https://arxiv.org/pdf/2207.04394.pdf'
url_code: 'https://github.com/VITA-Group/chext'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
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
slides: ""
---
