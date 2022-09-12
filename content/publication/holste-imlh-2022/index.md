---
title: "Self-Supervised Learning of Echocardiogram Videos Enables Data-Efficient Clinical Diagnosis"
authors:
- Gregory Holste
- Evangelos K. Oikonomou
- Bobak Mortazavi
- Zhangyang Wang
- Rohan Khera
date: "2022-07-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv Preprint"
publication_short: "arXiv"

abstract: 'Given the difficulty of obtaining high-quality labels for medical image recognition tasks, there is a need for deep learning techniques that can be adequately fine-tuned on small labeled data sets. Recent advances in self-supervised learning techniques have shown that such an in-domain representation learning approach can provide a strong initialization for supervised fine-tuning, proving much more data-efficient than standard transfer learning from a supervised pretraining task. However, these applications are not adapted to applications to medical diagnostics captured in a video format. With this progress in mind, we developed a self-supervised learning approach catered to echocardiogram videos with the goal of learning strong representations for downstream fine-tuning on the task of diagnosing aortic stenosis (AS), a common and dangerous disease of the aortic valve. When fine-tuned on 1% of the training data, our best self-supervised learning model achieves 0.818 AUC (95% CI: 0.794, 0.840), while the standard transfer learning approach reaches 0.644 AUC (95% CI: 0.610, 0.677). We also find that our self-supervised model attends more closely to the aortic valve when predicting severe AS as demonstrated by saliency map visualizations.'

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#3C94B5">arXiv Preprint</b><br> Self-supervised learning method for echocardiogram videos drives label-efficient fine-tuning on aortic stenosis classification. <b>Presented at <a href="https://sites.google.com/view/imlh2022/home">IMLH 2022</a>, an ICML workshop.</b>

tags:
- Source Themes
featured: true

url_pdf: 'https://arxiv.org/pdf/2207.11581.pdf'
url_code: 'https://github.com/CarDS-Yale/echo-ssl-aortic-stenosis'
url_dataset: ''
url_poster: 'https://gholste.me/media/imlh_2022_poster.pdf'
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
