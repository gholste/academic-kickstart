---
title: "Harnessing the power of longitudinal medical imaging for eye disease prognosis using Transformer-based sequence modeling"
authors:
- Gregory Holste
- Mingquan Lin
- Ruiwen Zhou
- Fei Wang
- Lei Liu
- Qi Yan
- Sarah H. Van Tassel
- Kyle Kovacs
- Emily Y. Chew
- Zhiyong Lu
- Zhangyang Wang
- Yifan Peng
date: "2024-08-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "npj Digital Medicine"
publication_short: "npj DM"

abstract: "Deep learning has enabled breakthroughs in automated diagnosis from medical imaging, with many successful applications in ophthalmology. However, standard medical image classification approaches only assess disease presence at the time of acquisition, neglecting the common clinical setting of longitudinal imaging. For slow, progressive eye diseases like age-related macular degeneration (AMD) and primary open-angle glaucoma (POAG), patients undergo repeated imaging over time to track disease progression and forecasting the future risk of developing disease is critical to properly plan treatment. Our proposed Longitudinal Transformer for Survival Analysis (LTSA) enables dynamic disease prognosis from longitudinal medical imaging, modeling the time to disease from sequences of fundus photography images captured over long, irregular time periods. Using longitudinal imaging data from the Age-Related Eye Disease Study (AREDS) and Ocular Hypertension Treatment Study (OHTS), LTSA significantly outperformed a single-image baseline in 19/20 head-to-head comparisons on late AMD prognosis and 18/20 comparisons on POAG prognosis. A temporal attention analysis also suggested that, while the most recent image is typically the most influential, prior imaging still provides additional prognostic value. "

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#3C94B5">npj Digital Medicine</b><br> Automated eye disease prognosis by survival analysis from longitudinal medical imaging.

tags:
- Source Themes
featured: true

url_source: 'https://www.nature.com/articles/s41746-024-01207-4'
url_pdf: 'https://www.nature.com/articles/s41746-024-01207-4.pdf'
url_code: 'https://github.com/bionlplab/longitudinal_transformer_for_survival_analysis'
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
