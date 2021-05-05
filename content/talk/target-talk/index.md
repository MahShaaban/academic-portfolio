---
abstract: Transcription factor binding to the regulatory region of a gene induces or represses its gene expression. Transcription factors share their binding sites with other factors, co-factors, and/or DNA-binding proteins. These proteins form complexes that bind to the DNA as one-units. The binding of two factors to a shared site does not always lead to a functional interaction. We propose a method to predict the combined functions of two factors using comparable binding and expression data (target). We based this method on binding and expression target analysis (BETA), which we re-implemented in R and extended for this purpose. target ranks the factor's targets by importance and predicts the dominant type of interaction between two transcription factors. We applied the method to simulated and real datasets of transcription factor-binding sites and gene expression under perturbation of factors. We found that Yin Yang 1 transcription factor (YY1) and YY2 have antagonistic and independent regulatory targets in HeLa cells, but they may cooperate on a few shared targets. We developed an R package and a web application to integrate binding (ChIP-seq) and expression (microarrays or RNA-seq) data to determine the cooperative or competitive combined function of two transcription factors.
address:
  city: Virtual
  country: ""
  postcode: ""
  region: ""
  street: ""
all_day: false
authors: []
date: "2020-08-25T00:00:00Z"
date_end: "2020-08-25T00:00:00Z"
event: KSBMB International Conference 2020
event_url: http://new.ksbmb.or.kr
featured: true
image:
  caption: ""
  focal_point: Right
location: Virtual
projects:
- transcription-regulation
publishDate: "2020-08-25T00:00:00Z"
slides: ""
summary: ""
tags: []
title: Integrating binding and expression data to predict transcription factors combined function
url_code: "https://github.com/MahShaaban/target_Shop_talk"
url_pdf: ""
url_slides: "static/media/target_slides.pdf"
url_video: ""
---

## Overview

Transcription factor binding to the regulatory region of a gene induces or represses its gene expression. Transcription factors share their binding sites with other factors, co-factors, and/or DNA-binding proteins. These proteins form complexes that bind to the DNA as one-units. The binding of two factors to a shared site does not always lead to a functional interaction. We propose a method to predict the combined functions of two factors using comparable binding and expression data (target). We based this method on binding and expression target analysis (BETA), which we re-implemented in R and extended for this purpose. target ranks the factor's targets by importance and predicts the dominant type of interaction between two transcription factors. We applied the method to simulated and real datasets of transcription factor-binding sites and gene expression under perturbation of factors. We found that Yin Yang 1 transcription factor (YY1) and YY2 have antagonistic and independent regulatory targets in HeLa cells, but they may cooperate on a few shared targets. We developed an R package and a web application to integrate binding (ChIP-seq) and expression (microarrays or RNA-seq) data to determine the cooperative or competitive combined function of two transcription factors.
