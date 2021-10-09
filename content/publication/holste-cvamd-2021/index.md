---
title: "End-to-End Learning of Fused Image and Non-Image Features for Improved Breast Cancer Classification from MRI"
authors:
- Gregory Holste
- Savannah Partridge
- Habib Rahbar
- Debosmita Biswas
- Christoph Lee
- Adam Alessio
date: "2021-10-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Computer Vision for Automated Medical Diagnosis (ICCV Workshop)*"
publication_short: "*CVAMD 2021*"

abstract: "Breast cancer diagnosis is inherently multimodal. To assess a patient’s cancer status, physicians integrate imaging findings with a variety of clinical risk factor data. Despite this, deep learning approaches for automatic breast cancer classification often only utilize image data or non-image clinical data, but not both simultaneously. In this work, we implemented and compared strategies for the fusion of imaging and tabular non-image data in an end-to-end trainable manner, evaluating fusion at different stages in the model (fusing intermediate features vs. output probabilities) and with different operations (concatenation vs. addition vs. multiplication). This retrospective study utilized dynamic contrast-enhanced MRI (DCE-MRI) data from 10,185 breast MRI examinations of 5,248 women. DCE-MRIs were reduced to 2D maximum intensity projections, split into single-breast images, then linked to a set of 18 non-image features including clinical indication and mammographic breast density. We first trained unimodal baseline models on images alone and non-image data alone. We then developed three multimodal fusion models that learn jointly from image and non-image data, evaluating performance by area under the receiver operating characteristic curve (AUC) and specificity at 95% sensitivity. The image-only baseline achieved an AUC of 0.849 (95% CI: 0.834, 0.864) and specificity at 95% sensitivity of 30.1% (95% CI: 23.1%, 37.0%), while the best-performing fusion model achieved an AUC of 0.898 (95% CI: 0.885, 0.909) and specificity of 49.1% (95% CI: 38.8%, 55.3%). Furthermore, all three fusion methods significantly outperformed both unimodal baselines with respect to AUC and specificity at 95% sensitivity. This work demonstrates in our dataset for breast cancer classification that incorporating non-image data with images can significantly improve predictive performance and that fusion of intermediate learned features is superior to fusion of final probabilities."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#3C94B5">CVAMD 2021 (ICCV Workshop)</b><br> Methods for jointly learning from breast imaging and tabular non-image data to predict breast cancer.

tags:
- Source Themes
featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: 'Holste_Poster_CVAMD2021.pdf'
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
