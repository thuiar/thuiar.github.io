---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Learning Modality-Specific Representations with Self-Supervised Multi-Task Learning for Multimodal Sentiment Analysis"
authors: [WenmengYu, HuaXu, ZiqiYuan, JieleWu]
date: 2021-02-15T18:38:46+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-02-15T18:38:46+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the AAAI Conference on Artificial Intelligence"
publication_short: "AAAI2021"

abstract: "Representation Learning is a significant and challenging task in multimodal learning. Effective modality representations should contain two parts of characteristics: the consistency and the difference. Due to the unified multimodal annotation, existing methods are restricted in capturing differentiated information. However, additional uni-modal annotations are high time- and labor-cost. In this paper, we design a label generation module based on the self-supervised learning strategy to acquire independent unimodal supervisions. Then, joint training the multi-modal and uni-modal tasks to learn the consistency and difference, respectively. Moreover, during the training stage, we design a weight-adjustment strategy to balance the learning progress among different subtasks. That is to guide the subtasks to focus on samples with a larger difference between modality supervisions. Last, we conduct extensive experiments on three public multimodal baseline datasets. The experimental results validate the reliability and stability of auto-generated unimodal supervisions. On MOSI and MOSEI datasets, our method surpasses the current state-of-the-art methods. On the SIMS dataset, our method achieves comparable performance than humanannotated unimodal labels."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2102.04830v1.pdf
url_code: https://github.com/thuiar/Self-MM
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
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
