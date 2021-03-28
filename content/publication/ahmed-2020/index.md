---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Integrating binding and expression data to predict transcription factors combined
  function
subtitle: ''
summary: ''
authors:
- Mahmoud Ahmed
- Do Sik Min
- Deok Ryong Kim
tags:
- 'BETA'
- 'Competitive-binding'
- 'Cooperative-binding'
- 'DNA-binding'
- 'R package'
- 'Transcription-factor'
- 'YY1'
categories: ["Methods"]
date: '2020-12-01'
lastmod: 2021-03-29T06:06:07Z
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["managing-tools","transcription-regulation"]
publishDate: '2021-03-29T06:06:06.875192Z'
publication_types:
- '2'
abstract: "Background: Transcription factor binding to the regulatory region of a\
  \ gene induces or represses its gene expression. Transcription factors share their\
  \ binding sites with other factors, co-factors and/or DNA-binding proteins. These\
  \ proteins form complexes which bind to the DNA as one-units. The binding of two\
  \ factors to a shared site does not always lead to a functional interaction. Results:\
  \ We propose a method to predict the combined functions of two factors using comparable\
  \ binding and expression data (target). We based this method on binding and expression\
  \ target analysis (BETA), which we re-implemented in R and extended for this purpose.\
  \ target ranks the factor's targets by importance and predicts the dominant type\
  \ of interaction between two transcription factors. We applied the method to simulated\
  \ and real datasets of transcription factor-binding sites and gene expression under\
  \ perturbation of factors. We found that Yin Yang 1 transcription factor (YY1) and\
  \ YY2 have antagonistic and independent regulatory targets in HeLa cells, but they\
  \ may cooperate on a few shared targets. Conclusion: We developed an R package and\
  \ a web application to integrate binding (ChIP-seq) and expression (microarrays\
  \ or RNA-seq) data to determine the cooperative or competitive combined function\
  \ of two transcription factors."
publication: '*BMC Genomics*'
url_pdf: https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-020-06977-1
doi: 10.1186/s12864-020-06977-1
---
