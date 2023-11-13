---
date: "2023-11-08T00:00:00Z"
external_link: ""
image:
  caption: "Individual Time-series Line Plot of Depressive Symptoms, Yama Chang © 2023"
  focal_point: Smart
# links:
# - icon: github
#   icon_pack: ai
#   name: Github
#   url: https://github.com/yamachang/ttt-p1-main-analysis
# - icon: osf
#   icon_pack: ai
#   name: Pre-registration
#   url: https://osf.io/c4e75/
slides: 
summary: 
tags:
- Machine Learning
- Digital Mental Health
title: Time-Series Prediction of Change in Depressive Symptoms
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

<p>In this project, we constructed an ML pipeline that predicted changes in the overall severity of depression symptoms in adolescents with high symptoms over a three-month period. We computed the residuals from a linear regression model, predicting the 3-month depression sum score based on the baseline depression sum score. These residuals, which represent the unexplained change over three months, were utilized to build a model that could capture factors not included in the baseline model.</p>

<p>The project entailed comprehensive model building, time-series feature engineering, data preprocessing, model evaluation, and validation to ensure the high quality of input data for the models and the accuracy and interpretability of the results. We trained and evaluated various regression algorithms, including Elastic Net, Random Forest, and Extreme Gradient Boosting, to assess their prediction performance.</p>

<p>Additionally, I visualized the time-series data to gain insights into the trends of eight depressive symptoms (e.g., sadness, energy, interest, etc.).</p>


<h6>Read more</h6>
<hr>
<span>We are currently drafting the manuscript. For detailed project information, please visit the GitHub repository or find the pre-registration on the Open Science Framework (OSF).</span>
<div style="margin-top: 5px;">
<a class="btn btn-primary btn text-uppercase js-scroll-trigger" href="https://github.com/yamachang/ttt-p1-main-analysis">Github</a>
                      <a class="btn btn-primary btn text-uppercase js-scroll-trigger" href="https://osf.io/c4e75/">Pre-registration</a>

