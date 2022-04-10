---
title: "Avalanche decision schemes to improve pediatric rib fracture detection"
authors:
- Jonathan Burkow
- Gregory Holste
- Jeffrey Otjen
- Francisco Perez
- Joseph Junewick
- Adam Alessio
date: "2022-04-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *SPIE Medical Imagin: Computer-Aided Diagnosis*"
publication_short: "*SPIE Medical Imaging 2022*"

abstract: "Rib fractures are a sentinel injury for physical abuse in young children. When rib fractures are detected in young children, 80-100% of the time it is the result of child abuse. Rib fractures can be challenging to detect on pediatric radiographs given that they can be non-displaced, incomplete, superimposed over other structures, or oriented obliquely with respect to the detector. This work presents our efforts to develop an object detection method for rib fracture detection on pediatric chest radiographs. We propose a method entitled “avalanche decision” motivated by the reality that pediatric patients with rib fractures commonly present with multiple fractures; in our dataset, 76% of patients with fractures had more than one fracture. This approach is applied at inference and uses a decision threshold that decreases as a function of the number of proposals that clear the current threshold. These contributions were added to two leading single stage detectors: RetinaNet and YOLOv5. These methods were trained and tested with our curated dataset of 704 pediatric chest radiographs, for which pediatric radiologists labeled fracture locations and achieved an expert reader-to-reader F2 score of 0.76. Comparing base RetinaNet to RetinaNet+Avalanche yielded F2 scores of 0.55 and 0.65, respectively. F2 scores of base YOLOv5 and YOLOv5+Avalanche were 0.58 and 0.65, respectively. The proposed avalanche inferencing approaches provide increased recall and F2 scores over the standalone models."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#3C94B5">SPIE Medical Imaging 2022</b><br> Domain knowledge-guided method for improved rib fracture localization.

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
