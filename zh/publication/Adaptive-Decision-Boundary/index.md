---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Deep Open Intent Classification with Adaptive Decision Boundary"
authors: [HanleiZhang, HuaXu, TingenLin]
date: 2021-02-16T18:38:46+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-02-16T18:38:46+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the AAAI Conference on Artificial Intelligence"
publication_short: "AAAI2021"

abstract: "Open intent classification is a challenging task in dialogue systems. On the one hand, we should ensure the classification quality of known intents. On the other hand, we need to identify the open (unknown) intent during testing. Current models are limited in finding the appropriate decision boundary to balance the performances of both known and open intents. In this paper, we propose a post-processing method to learn the adaptive decision boundary (ADB) for open intent classification. We first utilize the labeled known intent samples to pre-train the model. Then, we use the well-trained features to automatically learn the adaptive spherical decision boundaries for each known intent. Specifically, we propose a new loss function to balance both the empirical risk and the open space risk. Our method does not need open samples and is free from modifying the model architecture. We find our approach is surprisingly insensitive with less labeled  data and fewer known intents. Extensive experiments on three benchmark datasets show that our method yields significant improvements compared with the state-of-the-art methods."

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

url_pdf: https://arxiv.org/pdf/2012.10209.pdf
url_code: https://github.com/thuiar/Adaptive-Decision-Boundary
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
