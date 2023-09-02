---
title: "Severe aortic stenosis detection by deep learning applied to echocardiography"
authors:
- Gregory Holste
- Evangelos K. Oikonomou
- Bobak J. Mortazavi
- Andreas Coppi
- Kamil F. Faridi
- Edward J. Miller
- John K. Forrest
- Robert L. McNamara
- Lucila Ohno-Machado
- Neal Yuan
- Aakriti Gupta
- David Ouyang
- Harlan M. Krumholz
- Zhangyang Wang
- Rohan Khera
date: "2023-08-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "European Heart Journal"
publication_short: "EHJ"

abstract: 'Background and Aims: Early diagnosis of aortic stenosis (AS) is critical to prevent morbidity and mortality but requires skilled examination with Doppler imaging. This study reports the development and validation of a novel deep learning model that relies on two-dimensional (2D) parasternal long axis videos from transthoracic echocardiography without Doppler imaging to identify severe AS, suitable for point-of-care ultrasonography.

Methods and results: In a training set of 5257 studies (17 570 videos) from 2016 to 2020 [Yale-New Haven Hospital (YNHH), Connecticut], an ensemble of three-dimensional convolutional neural networks was developed to detect severe AS, leveraging self-supervised contrastive pretraining for label-efficient model development. This deep learning model was validated in a temporally distinct set of 2040 consecutive studies from 2021 from YNHH as well as two geographically distinct cohorts of 4226 and 3072 studies, from California and other hospitals in New England, respectively. The deep learning model achieved an area under the receiver operating characteristic curve (AUROC) of 0.978 (95% CI: 0.966, 0.988) for detecting severe AS in the temporally distinct test set, maintaining its diagnostic performance in geographically distinct cohorts [0.952 AUROC (95% CI: 0.941, 0.963) in California and 0.942 AUROC (95% CI: 0.909, 0.966) in New England]. The model was interpretable with saliency maps identifying the aortic valve, mitral annulus, and left atrium as the predictive regions. Among non-severe AS cases, predicted probabilities were associated with worse quantitative metrics of AS suggesting an association with various stages of AS severity.

Conclusion: This study developed and externally validated an automated approach for severe AS detection using single-view 2D echocardiography, with potential utility for point-of-care screening.'

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#3C94B5">European Heart Journal</b><br> Accurate and generalizable detection of severe aortic stenosis based on single-view echocardiography.

tags:
- Source Themes
featured: true

url_source: 'https://academic.oup.com/eurheartj/advance-article/doi/10.1093/eurheartj/ehad456/7248551'
url_pdf: ''
url_code: 'https://github.com/CarDS-Yale/echo-severe-AS'
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
