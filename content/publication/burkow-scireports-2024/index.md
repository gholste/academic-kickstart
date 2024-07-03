---
title: "High sensitivity methods for automated rib fracture detection in pediatric radiographs"
authors:
- Jonathan Burkow
- Gregory Holste
- Jeffrey Otjen
- Francisco Perez
- Joseph Junewick
- Andy Zbojniewicz
- Erin Romberg
- Sarah Menashe
- Jamie Frost
- Adam Alessio
date: "2024-04-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Scientific Reports"
publication_short: "Scientific Reports"

abstract: "Rib fractures are highly predictive of non-accidental trauma in children under 3 years old. Rib fracture detection in pediatric radiographs is challenging because fractures can be obliquely oriented to the imaging detector, obfuscated by other structures, incomplete, and non-displaced. Prior studies have shown up to two-thirds of rib fractures may be missed during initial interpretation. In this paper, we implemented methods for improving the sensitivity (i.e. recall) performance for detecting and localizing rib fractures in pediatric chest radiographs to help augment performance of radiology interpretation. These methods adapted two convolutional neural network (CNN) architectures, RetinaNet and YOLOv5, and our previously proposed decision scheme, “avalanche decision”, that dynamically reduces the acceptance threshold for proposed regions in each image. Additionally, we present contributions of using multiple image pre-processing and model ensembling techniques. Using a custom dataset of 1109 pediatric chest radiographs manually labeled by seven pediatric radiologists, we performed 10-fold cross-validation and reported detection performance using several metrics, including F2 score which summarizes precision and recall for high-sensitivity tasks. Our best performing model used three ensembled YOLOv5 models with varied input processing and an avalanche decision scheme, achieving an F2 score of 0.725 ± 0.012. Expert inter-reader performance yielded an F2 score of 0.732. Results demonstrate that our combination of sensitivity-driving methods provides object detector performance approaching the capabilities of expert human readers, suggesting that these methods may provide a viable approach to identify all rib fractures."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#3C94B5">Scientific Reports</b><br> Ensemble methods for automated pediatric rib fracture detection on chest X-ray.

tags:
- Source Themes
featured: true

url_source: 'https://www.nature.com/articles/s41598-024-59077-5'
url_pdf: 'https://www.nature.com/articles/s41598-024-59077-5.pdf'
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
