---
abstract: Researchers use ChIP binding data to identify potential transcription factor binding sites. They use gene expression data from sequencing or microarrays to quantify the effect of the factor over-expression or knockdown on its targets. The integration of the binding and expression data therefore can be used to improve the understanding of a transcription factor function. In this workshop, I present a complete workflow for integrating the gene expression (RNA-seq) and DNA-binding data (ChIP-seq) to predict the combined function of two transcription factors using R/Bioconductor. The example we will be using in the workshop is from real datasets of two functionally and evolutionary related transcription factors YY1 and YY2 in HeLa cells. We will try to identify the factor-specific and the shared targets of the factors in this particular cell line. Then we will use a technique find out the aggregate functions of the factors on their individual (inducer or repressor) and common targets (cooperative or competitive). The first half of the workshop would be dedicated to introduce the target package followed by a walk through the workflow interactively in a live demo in the second half.
address:
  city: Virtual
  country: ""
  postcode: ""
  region: ""
  street: ""
all_day: false
authors: []
date: "2020-12-17T17:30:00Z"
date_end: "2020-12-17T18:15:00Z"
event: European Bioconductor Meeting 2020
event_url: https://eurobioc2020.bioconductor.org/
featured: true
image:
  caption: ""
  focal_point: Right
links:
- icon: link
  icon_pack: fas
  name: Link
  url: https://mahshaaban.github.io/targetShop/
location: Virtual
projects:
- transcription-regulation
publishDate: "2020-12-17T18:15:00Z"
slides: ""
summary: ""
tags: []
title: Integrating ChIP-seq and RNA-seq data in R
url_code: "https://github.com/MahShaaban/targetShop"
url_pdf: ""
url_slides: ""
url_video: "https://www.youtube.com/watch?v=y-z2r4tTLrI&list=PLdl4u5ZRDMQQDcVmINe4uXCq-89bxh71v&index=29"
---

- The materials were presented at 
[EuropBioc 2021](https://github.com/MahShaaban/targetShop). 
- The code is organized in a 
[BiocWorkshop](https://github.com/seandavi/BuildABiocWorkshop) format.


## Overview

Researchers use ChIP binding data to identify potential transcription factor binding sites. They use gene expression data from sequencing or microarrays to quantify the effect of the factor over-expression or knockdown on its targets. The integration of the binding and expression data therefore can be used to improve the understanding of a transcription factor function. In this workshop, I present a complete workflow for integrating the gene expression (RNA-seq) and DNA-binding data (ChIP-seq) to predict the combined function of two transcription factors using R/Bioconductor. The example we will be using in the workshop is from real datasets of two functionally and evolutionary related transcription factors YY1 and YY2 in HeLa cells. We will try to identify the factor-specific and the shared targets of the factors in this particular cell line. Then we will use a technique find out the aggregate functions of the factors on their individual (inducer or repressor) and common targets (cooperative or competitive). The first half of the workshop would be dedicated to introduce the target package followed by a walk through the workflow interactively in a live demo in the second half.