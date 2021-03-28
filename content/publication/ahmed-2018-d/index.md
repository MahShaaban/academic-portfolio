---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'pcr: an R package for quality assessment, analysis and testing of qPCR data.'
subtitle: ''
summary: ''
authors:
- Mahmoud Ahmed
- Deok Ryong Kim
tags:
- 'Data analysis'
- 'Quality assessment'
- 'R package'
- 'qPCR'
categories: ["Software"]
date: '2018-03-01'
lastmod: 2021-03-29T06:06:03Z
featured: false
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
projects: ["managing-tools"]
publishDate: '2021-03-29T06:06:02.544314Z'
publication_types:
- '2'
abstract: Background Real-time quantitative PCR (qPCR) is a broadly used technique
  in the biomedical research. Currently, few different analysis models are used to
  determine the quality of data and to quantify the mRNA level across the experimental
  conditions. Methods We developed an R package to implement methods for quality assessment,
  analysis and testing qPCR data for statistical significance. Double Delta C T and
  standard curve models were implemented to quantify the relative expression of target
  genes from C T in standard qPCR control-group experiments. In addition, calculation
  of amplification efficiency and curves from serial dilution qPCR experiments are
  used to assess the quality of the data. Finally, two-group testing and linear models
  were used to test for significance of the difference in expression control groups
  and conditions of interest. Results Using two datasets from qPCR experiments, we
  applied different quality assessment, analysis and statistical testing in the pcr
  package and compared the results to the original published articles. The final relative
  expression values from the different models, as well as the intermediary outputs,
  were checked against the expected results in the original papers and were found
  to be accurate and reliable. Conclusion The pcr package provides an intuitive and
  unified interface for its main functions to allow biologist to perform all necessary
  steps of qPCR analysis and produce graphs in a uniform way.
publication: '*PeerJ*'
url_pdf: https://peerj.com/articles/4473 http://www.ncbi.nlm.nih.gov/pubmed/29576953
  http://www.pubmedcentral.nih.gov/articlerender.fcgi?artid=PMC5858653
doi: 10.7717/peerj.4473
---
