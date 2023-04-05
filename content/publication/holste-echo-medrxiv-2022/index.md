---
title: "Automated severe aortic stenosis detection on single-view echocardiography: A multi-center deep learning study"
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
date: "2022-12-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "medRxiv Preprint"
publication_short: "medRxiv"

abstract: 'Background and Aims: Early diagnosis of aortic stenosis (AS) is critical to prevent morbidity and mortality but requires skilled examination with Doppler imaging. This study reports the development and validation of a novel deep learning model that relies on 2-dimensional parasternal long axis (PLAX) videos from transthoracic echocardiography (TTE) without Doppler imaging to identify severe AS, suitable for point-of-care ultrasonography.

Methods: In a training set of 5,257 studies (17,570 videos) from 2016-2020 (Yale-New Haven Hospital [YNHH], Connecticut), an ensemble of 3-dimensional convolutional neural networks was developed to detect severe AS, leveraging self-supervised contrastive pretraining for label-efficient model development. This deep learning model was validated in a temporally distinct set of 2,040 consecutive studies from 2021 from YNHH as well as two geographically distinct cohorts of 5,572 and 865 studies, from California and other hospitals in New England, respectively.

Results: The deep learning model achieved an AUROC of 0.978 (95% CI: 0.966, 0.988) for detecting severe AS with 95.4% specificity and 90% sensitivity in the temporally distinct test set, maintaining its diagnostic performance in both geographically distinct cohorts (AUROC 0.972 [95% CI: 0.969, 0.975] in California and 0.915 [95% CI: 0.896, 0.933] in New England, respectively). The model was interpretable with saliency maps identifying the aortic valve as the predictive region. Among non-severe AS cases, predicted probabilities were associated with worse quantitative metrics of AS suggesting association with various stages of AS severity.

Conclusions: This study developed and externally validated an automated approach for severe AS detection using single-view 2D echocardiography, with implications for point-of-care screening.'

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#3C94B5">medRxiv Preprint</b><br> Accurate and generalizable detection of severe aortic stenosis based on single-view echocardiography.

tags:
- Source Themes
featured: true

url_pdf: 'https://www.medrxiv.org/content/10.1101/2022.08.30.22279413v2.full.pdf'
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
