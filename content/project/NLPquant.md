---
title: Stock Selection Alpha-Factor for Chinese Stock Market Based on Sentiment Analysis
summary: An implement of NLP skills in quantitative finance.
tags:
- Deep Learning
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Follow
  url: https://github.com/YiyangZhang0201/EECS595-FINAL
url_code: ""
url_pdf: "https://github.com/YiyangZhang0201/EECS595-FINAL/blob/main/Yiyang%20Zhang%20EECS%20595%20Final%20Project.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

In this project, we collected the news for stocks in SSE 50 Index of the Chinese stock market and use the sentiment analysis to do the multiclassification on the related news. The news will be classified to five different labels and each stands for different market sentiment related to the stocks. In this multi-class sentiment analysis task, we used BERT model and LSTM model. Then, we mark their prediction result on the new incoming news with different score based on the label and do the ranking based on the scores. Then, we have got several Rank factors based on this method and test its effectiveness by comparing its performance with the benchmark portfolio based on SSE 50 Index. The conclusion is the BERT model and LSTM model performs similarly on this task with accuracy around 75% and the Rank factors we got are effective Augmentation Index Factors. The IR of this ranking method factor is 0.459 and the IC is about 0.044, which means the factors coming from this ranking method has a relative strong ability to gain excess return.
