---
title: A Factor-Based Alpha Investment Strategy Using Machine Learning
summary: Trying to find alpha-factors for stock market use Machine Learning and build trading strategy based on the factors we got.
tags:
- Financial Engineering
date: "2022-04-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Follow
  url: https://github.com/YiyangZhang0201/STATS503-FINAL/blob/main/STATS503_FinalReport_Group22-2.pdf
url_code: ""
url_pdf: "https://github.com/YiyangZhang0201/STATS503-FINAL/blob/main/STATS503_FinalReport_Group22-2.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

With the development of the finance market and technology, the quantitative trading plays an increasingly important role in financial markets around the world. Among various trading strategies,
factor-based alpha investment structures are the mostly used medium or low frequency trading strategies in stock markets. In this project, we experiment with different machine learning techniques to
find an alpha factor of the stock market and evaluate them from different aspects. Moreover, we build
a factor-based alpha investment strategy based on the alpha factor we obtained. The stock market
we chose is the SSE 50 Index, a representative stock market index of the Shanghai Stock Exchange in
China.

The final results show that Lasso Regression and Random Forest models achieve the best performance. Both models return us a factor that has mean Information Coefficient (IC) equal to 0.036
and 0.216, and Information Ratio (IR) equal to 0.232 and 1.276. Therefore, both alpha factors based
on these two models have significant power in earning excess return and beating the market. In the
out-of-sample back-testing experiment, based on the trading strategy built upon our models, we obtain an excess return of 10.72% and 9.15% over the simple buy-and-hold strategy on SSE 50 Index.
This shows that our factor building methods through machine learning and our factor-based trading
strategies have the significant power in beating the market and getting excess return.

