---
title: "Biometric contrastive learning for data-efficient deep learning from electrocardiographic images"
authors:
- Veer Sangha
- Akshay Khunte
- Gregory Holste
- Bobak J. Mortazavi
- Zhangyang Wang
- Evangelos K Oikonomou
- Rohan Khera
date: "2024-01-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of the American Medical Informatics Association"
publication_short: "JAMIA"

abstract: "**Objective**: Artificial intelligence (AI) detects heart disease from images of electrocardiograms (ECGs). However, traditional supervised learning is limited by the need for large amounts of labeled data. We report the development of Biometric Contrastive Learning (BCL), a self-supervised pretraining approach for label-efficient deep learning on ECG images.<br />
**Materials and Methods**: Using pairs of ECGs from 78,288 individuals from Yale (2000-2015), we trained a convolutional neural network to identify temporally separated ECG pairs that varied in layouts from the same patient. We fine-tuned BCL-pretrained models to detect atrial fibrillation (AF), gender, and LVEF < 40%, using ECGs from 2015 to 2021. We externally tested the models in cohorts from Germany and the United States. We compared BCL with ImageNet initialization and general-purpose self-supervised contrastive learning for images (simCLR).<br />
**Results**: While with 100% labeled training data, BCL performed similarly to other approaches for detecting AF/Gender/LVEF < 40% with an AUROC of 0.98/0.90/0.90 in the held-out test sets, it consistently outperformed other methods with smaller proportions of labeled data, reaching equivalent performance at 50% of data. With 0.1% data, BCL achieved AUROC of 0.88/0.79/0.75, compared with 0.51/0.52/0.60 (ImageNet) and 0.61/0.53/0.49 (simCLR). In external validation, BCL outperformed other methods even at 100% labeled training data, with an AUROC of 0.88/0.88 for Gender and LVEF < 40% compared with 0.83/0.83 (ImageNet) and 0.84/0.83 (simCLR).<br />
**Discussion and Conclusion**:A pretraining strategy that leverages biometric signatures of different ECGs from the same patient enhances the efficiency of developing AI models for ECG images. This represents a major advance in detecting disorders from ECG images with limited labeled data."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#3C94B5">JAMIA</b><br> Label-efficient electrocardiogram (ECG) image classification with contrastive learning.

tags:
- Source Themes
featured: true

url_source: 'https://academic.oup.com/jamia/article-abstract/31/4/855/7588722?redirectedFrom=fulltext'
url_pdf: 'https://www.medrxiv.org/content/10.1101/2023.09.13.23295494v1.full.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
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
