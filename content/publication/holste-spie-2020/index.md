---
title: "Multi-class semantic segmentation of pediatric chest radiographs"
authors:
- Gregory Holste
- Ryan Sullivan
- Michael Bindschadler
- Nicholas Nagy
- Adam Alessio
date: "2020-03-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *SPIE Medical Imaging: Image Processing*"
publication_short: "*SPIE Medical Imaging 2020*"

abstract: "Chest radiographs are a common diagnostic tool in pediatric care, and several computer-augmented decision tasks for radiographs would benefit from knowledge of the anatomic locations within the thorax. For example, a pre-segmented chest radiograph could provide context for algorithms designed for automatic grading of catheters and tubes. This work develops a deep learning approach to automatically segment chest radiographs into multiple regions to provide anatomic context for future automatic methods. This type of segmentation offers challenging aspects in its goal of multi-class segmentation with extreme class imbalance between regions. In an IRB-approved study, pediatric chest radiographs were collected and annotated with custom software in which users drew boundaries around seven regions of the chest: left and right lung, left and right subdiaphragm, spine, mediastinum, and carina. We trained a U-Net-style architecture on 328 annotated radiographs, comparing model performance with various combinations of loss functions, weighting schemes, and data augmentation. On a test set of 70 radiographs, our best-performing model achieved 93.8% mean pixel accuracy and a mean Dice coefficient of 0.83. We find that (1) cross-entropy consistently outperforms generalized Dice loss, (2) light augmentation, including random rotations, improves overall performance, and (3) pre-computed pixel weights that account for class frequency provide small performance boosts. Overall, our approach produces realistic eight-class chest segmentations that can provide anatomic context for line placement and potentially other medical applications."

# Summary. An optional shortened abstract.
summary: <b SPIE Medical Imaging 2020></b> <b Oral></b><br> Automatic anatomic segmentation of pediatric chest radiographs under severe class imbalance.

tags:
- Source Themes
featured: true

url_pdf: ''
url_code: ''
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
