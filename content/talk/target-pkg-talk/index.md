---
abstract: Transcription factor binding to the regulatory region of a gene induces or represses its gene expression. Transcription factors share their binding sites with other factors, co-factors and/or DNA-binding proteins. These proteins form complexes which bind to the DNA as one-units. The binding of two factors to a shared site does not always lead to a functional interaction. We propose a method to predict the combined functions of two factors using comparable binding and expression data (target). We based this method on binding and expression target analysis (BETA), which we re-implemented in R and extended for this purpose. target ranks the factor's targets by importance and predicts the dominant type of interaction between two transcription factors. We applied the method to simulated and real datasets of transcription factor-binding sites and gene expression under perturbation of factors. We found that Yin Yang 1 transcription factor (YY1) and YY2 have antagonistic and independent regulatory targets in HeLa cells, but they may cooperate on a few shared targets. We developed an R package and a web application to integrate binding (ChIP-seq) and expression (microarrays or RNA-seq) data to determine the cooperative or competitive combined function of two transcription factors.
address:
  city: Virtual
  country: ""
  postcode: ""
  region: ""
  street: ""
all_day: false
authors: []
date: "2020-10-15T10:30:00Z"
date_end: "2020-10-15T11:00:00Z"
event: BiocAsia 2020
event_url: https://biocasia2020.bioconductor.org
featured: false
image:
  caption: ""
  focal_point: Right
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/search?q=%23EuroBioc2020
location: Virtual
projects:
- internal-project
publishDate: "2020-10-15T11:00:00Z"
slides: ""
summary: ""
tags: []
title: target; An R package to Predict Combined Function of Transcription Factors
url_code: https://github.com/MahShaaban/target_Shop_pkg_talk
url_pdf: ""
url_slides: "static/target_pkg_slides.pdf"
url_video: "https://www.youtube.com/"
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page.
