---
title: "Stock Volatility Prediction with Hybrid Model of FFNN and Lightgbm"
authors:
- admin
date: "2022-04-15"
doi: "10.1109/ICSP54964.2022.9778512"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-05-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2022 7th International Conference on Intelligent Computing and Signal Processing (ICSP)"
publication_short: "IEEE"

abstract: The existing prediction system for realized volatility is limited and cannot effectively de-scribe the stocks’ highly complex and nonlinear characters. In this study, we built a hybrid model by combining Feedforward Neural Network (FFNN) with Light Gradient Boosting Machine (LightGBM). Then we extract three important categories of features based on high frequency stock trading and quotation data, feed them into the hybrid model for predicting volatility, and test it on the real-market data in the next three months. We also compared our hybrid model with other models in the experiment process. Compared with traditional machine learning models like Naïve Bayes and SVM, or the single Lightgbm model, our hybrid model has the lowest RMSPE result of 0.192. And in the following three-month realmarket data test, our hybrid model’s RMSPE result remained in range [0.199, 0.219]. This test result further demonstrates the accuracy and robustness of our model’s out-of-sample performance.

# Summary. An optional shortened abstract.
summary: Realized volatility, High Frequency Data, LightGBM, FFNN, RMSPE, real-market test

tags:
- Source Themes
featured: true

url_pdf: 'https://github.com/YiyangZhang0201/KAGGLE-OPTIVER/blob/main/Stock_Volatility_Prediction_with_Hybrid_Model.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/fiXLQXAhCfk)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

