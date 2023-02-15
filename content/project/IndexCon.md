---
title: Index Fund Construction
summary: An implement of Subgradient Method in quantitative finance.
tags:
- Financial Engineering
date: "2021-12-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Follow
  url: https://github.com/YiyangZhang0201/Index-Construction
url_code: ""
url_pdf: "https://github.com/YiyangZhang0201/Index-Construction/blob/main/STATS_606_PROJECT%20Final%20Report.pdf"
url_slides: "https://github.com/YiyangZhang0201/Index-Construction/blob/main/Index_construction.ipynb"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

n the example, we use Subgradient algorithm we built in our package to 
do the optimization for the mathematical model we built. We want to use this model to construct an 
Index fund by using only part of its corresponding market Index’s components. And based on the result 
of the optimization, we test the optimal model on the out-of-sample period and found that it is highly 
effective. Our constructed Index follows the trend of corresponding Market Index pretty well.
