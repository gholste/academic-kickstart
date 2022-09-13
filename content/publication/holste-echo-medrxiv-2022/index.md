---
title: "Automated detection of severe aortic stenosis using single-view echocardiography: A self-supervised ensemble learning approach"
authors:
- Gregory Holste
- Evangelos K. Oikonomou
- Bobak J. Mortazavi
- Kamil F. Faridi
- Edward J. Miller
- John K. Forrest
- Robert L. McNamara
- Harlan M. Krumholz
- Zhangyang Wang
- Rohan Khera
date: "2022-08-31T00:00:00Z"
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

abstract: 'Given the difficulty of obtaining high-quality labels for medical image recognition tasks, there is a need for deep learning techniques that can be adequately fine-tuned on small labeled data sets. Recent advances in self-supervised learning techniques have shown that such an in-domain representation learning approach can provide a strong initialization for supervised fine-tuning, proving much more data-efficient than standard transfer learning from a supervised pretraining task. However, these applications are not adapted to applications to medical diagnostics captured in a video format. With this progress in mind, we developed a self-supervised learning approach catered to echocardiogram videos with the goal of learning strong representations for downstream fine-tuning on the task of diagnosing aortic stenosis (AS), a common and dangerous disease of the aortic valve. When fine-tuned on 1% of the training data, our best self-supervised learning model achieves 0.818 AUC (95% CI: 0.794, 0.840), while the standard transfer learning approach reaches 0.644 AUC (95% CI: 0.610, 0.677). We also find that our self-supervised model attends more closely to the aortic valve when predicting severe AS as demonstrated by saliency map visualizations.'

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#3C94B5">medRxiv Preprint</b><br> Accurate detection of severe aortic stenosis based on self-supervised and ensemble learning of single-view echocardiograms.

tags:
- Source Themes
featured: true

url_pdf: 'https://www.medrxiv.org/content/10.1101/2022.08.30.22279413v1.full.pdf'
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