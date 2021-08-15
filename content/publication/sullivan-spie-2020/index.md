---
title: "Deep learning methods for segmentation of lines in pediatric chest radiographs"
authors:
- Ryan Sullivan
- Gregory Holste
- Jonathan Burkow
- Adam Alessio
date: "2020-03-16T00:00:00Z"
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
publication_short: []

abstract: "Surgical procedures often require the use of catheters, tubes, and lines, collectively called lines. Misplaced lines can cause serious complications, such as pneumothorax, cardiac perforation, or thrombosis. To prevent these problems, radiologists examine chest radiographs after insertion and throughout intensive care to evaluate their placement. This process is time consuming, and incorrect interpretations occur with notable frequency. Fast and reliable automatic interpretations could potentially reduce the cost of these surgical operations, decrease the workload of radiologists, and improve the quality of care for patients. We develop a segmentation model which can highlight the medically relevant lines in pediatric chest radiographs using deep learning. We propose a two-stage segmentation network which first classifies whether images have medically relevant lines and then segments images with lines. For the segmentation stage, we use the popular U-Net architecture substituting the encoder path with multiple state-of-the-art CNN encoders. Our study compares the performance of different permutations of model architectures for the task of highlighting lines in pediatric chest radiographs and demonstrates the effectiveness of the two-stage architecture."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#3C94B5">SPIE Medical Imaging 2020</b><br> Segmentation methods for localizing "lines" (catheters, tubes, etc.) in pediatric chest radiographs.

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
