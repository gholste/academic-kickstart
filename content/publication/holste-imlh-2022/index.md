---
title: "Efficient deep learning-based automated diagnosis from echocardiography with contrastive self-supervised learning"
authors:
- Gregory Holste
- Evangelos K. Oikonomou
- Bobak Mortazavi
- Zhangyang Wang
- Rohan Khera
date: "2024-07-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Communications Medicine"
publication_short: "Communications Medicine"

abstract: "**Background**: Advances in self-supervised learning (SSL) have enabled state-of-the-art automated medical image diagnosis from small, labeled datasets. This label efficiency is often desirable, given the difficulty of obtaining expert labels for medical image recognition tasks. However, most efforts toward SSL in medical imaging are not adapted to video-based modalities, such as echocardiography.<br />
**Methods**: We developed a self-supervised contrastive learning approach, EchoCLR, for echocardiogram videos with the goal of learning strong representations for efficient fine-tuning on downstream cardiac disease diagnosis. EchoCLR pretraining involves (i) contrastive learning, where the model is trained to identify distinct videos of the same patient, and (ii) frame reordering, where the model is trained to predict the correct of video frames after being randomly shuffled.<br />
**Results**: When fine-tuned on small portions of labeled data, EchoCLR pretraining significantly improves classification performance for left ventricular hypertrophy (LVH) and aortic stenosis (AS) over other transfer learning and SSL approaches across internal and external test sets. When fine-tuning on 10% of available training data (519 studies), an EchoCLR-pretrained model achieves 0.72 AUROC (95% CI: [0.69, 0.75]) on LVH classification, compared to 0.61 AUROC (95% CI: [0.57, 0.64]) with a standard transfer learning approach. Similarly, using 1% of available training data (53 studies), EchoCLR pretraining achieves 0.82 AUROC (95% CI: [0.79, 0.84]) on severe AS classification, compared to 0.61 AUROC (95% CI: [0.58, 0.65]) with transfer learning."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#3C94B5">Communications Medicine</b><br> EchoCLR, a label-efficient self-supervised learning method for echocardiography.</b>

tags:
- Source Themes
featured: true

url_pdf: 'https://www.nature.com/articles/s43856-024-00538-3.pdf'
url_code: 'https://github.com/CarDS-Yale/echo-ssl-aortic-stenosis'
url_dataset: ''
url_poster: 'https://gholste.me/media/imlh_2022_poster.pdf'
url_project: ''
url_slides: ''
url_source: 'https://www.nature.com/articles/s43856-024-00538-3'
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
