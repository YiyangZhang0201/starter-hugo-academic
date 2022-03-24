---
title: Statistical Analysis for New Taipei Housing Litigation
summary: Statistical Analysis using GAM with B-spline.
tags:
- Statistical Analysis
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
  url: https://github.com/YiyangZhang0201/STATS-504
url_code: ""
url_pdf: "https://github.com/YiyangZhang0201/STATS-504/blob/main/STATS%20504%20HW4%20FINAL.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

For the real estate industry, statistical models are helpful to assess the price of real estate in one particular housing area. However, the price of a real estate unit can be influenced by various factors, like the housing age, geographical location, and house age, which brings many difficulties for the process of price appraisal. Our client tried to refer to some papers in the journal to get help with the data modeling and prediction task, but the statistical models suggested are way more complicated to understand, especially for non-statisticians. Also, though these models may give relatively accurate predictions, they may lose some interpretability. Since it is also important for our client to know how other factors affect the price, compared to giving out good final price estimations, we decided to construct a model that is easy to interpret and gives relatively precise price estimations.

Our final choice for our client is a spline model, which treats variables differently according to their values, allowing a more flexible model fit. Specifically, we developed a general additive model (GAM) with B-splines for some covariates. It performed well in the prediction task, and its results are also easy to interpret, which make it perfectly suit our client's need.
