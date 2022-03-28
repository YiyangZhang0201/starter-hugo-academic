---
title: "Stock Volatility Prediction with Hybrid Model"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin


# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2022-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Signal Processing*
publication_short: In *ICSP*

abstract: The existing prediction system for realized volatility is limited and cannot effectively de-scribe the stocks’ highly complex and nonlinear characters. In this study, we built a hybrid model by combining Feedforward Neural Network (FFNN) with Light Gradient Boosting Machine (LightGBM). Then we extract three important categories of features based on high frequency stock trading and quotation data, feed them into the hybrid model for predicting volatility, and test it on the real-market data in the next three months. We also compared our hybrid model with other models in the experiment process. Compared with traditional machine learning models like Naïve Bayes and SVM, or the single Lightgbm model, our hybrid model has the lowest RMSPE result of 0.192. And in the following three-month realmarket data test, our hybrid model’s RMSPE result remained in range $[0.199, 0.219]$. This test result further demonstrates the accuracy and robustness of our model’s out-of-sample performance.

# Summary. An optional shortened abstract.
summary: Realized volatility, High Frequency Data, LightGBM, FFNN, RMSPE, real-market test

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}
