---
layout: page
title: Home Projects
permalink: /homeprojects/
---

## Home Projects

#### Kaggle

I've spent many, many hours on **Kaggle** over the years, working on data-set projects, along with uploading my own collated and uploaded datasets. In fact, it was Kaggle that first introduced me to a lot of data-science concepts and tools. Here are some of my favourite mini-projects...  

  - [What Causes Heart Disease? Explaining the Model](https://www.kaggle.com/tentotheminus9/what-causes-heart-disease-explaining-the-model){:target="_blank"}: A challenge set by Kaggle to create a notebook that included a machine-learning model of some sort, and then to use various tools and techniques (**purmutation importance**, **SHAP values** and **partial plots**) to explain what the model was doing. This notebook on **machine-learning interpretability** won 'kernel of the month'
  
<img src="/images/heart.png" alt="Heart disease factors" width="400"/>
  
  - [Breakthrough Listen: L-Band Data](https://www.kaggle.com/tentotheminus9/l-band-2017){:target="_blank"}: My favourite hobby project to date, and one which kept me busy on many evenings and weekends. I started to look into data by SETI (the Search for Extraterrestrial Intelligence) after seeing that they'd openly shared a huge collection of datasets. I uploaded some of the data to Kaggle and created this notebook, which recreates the findings from a research paper. I also uploaded some more data and created a **deep learning** model in **keras** to classify signal types (see [here](SETI Simulated Signals - InceptionResNetV2)). Finally, I created some Python notebooks on **Google Cloud Platform** that did some novel data processing with SETI data. The files are on Github [here](https://github.com/RobHarrand/SETI_GCP)  
  
<img src="/images/seti.png" alt="SETI data" width="400"/>
  
  - [Kaggle Kernels bot mini-challenge](https://github.com/RobHarrand/kaggle-bot){:target="_blank"}: A challenge set by Kaggle to create a 'bot' that does something interesting on a Kaggle dataset. I created an R script that asks the user for a dataset, creates a new notebook for it via the Kaggle API, finds a CSV file, tries to figure out which column is the target variable, removes certain columns, imputes certain values, then applies 3 machine learning models and displays a **ROC plot** 
  
  - [Normal vs Pneumonia - Keras in R](https://www.kaggle.com/tentotheminus9/normal-vs-pneumonia-keras-in-r){:target="_blank"}: A notebook that uses keras to create a deep learning model, to tell the difference between normal and diseased radiograph images 
  
<img src="/images/xray.png" alt="ROC plot" width="300"/>
  
  - [So, You Have a Diagnostic Test Result](https://www.kaggle.com/tentotheminus9/so-you-have-a-diagnostic-test-result){:target="_blank"}: A lengthy notebook detailing the statistics behind diagnostic testing  

<img src="/images/diag.png" alt="Prior to posterior probability" width="300"/>
 
- Covid19 cases over time animation in R, using data from the UK government [Covid19 website](https://coronavirus.data.gov.uk/details/download){:target="_blank"}, GitHub gist for the code [here](https://gist.github.com/RobHarrand/5c9e35d10a37fe3fa4d527d7504dedbf){:target="_blank"}

<img src="/images/covid_uk.gif" alt="Covid19 animation" width="700"/>
 
- [Deep Learning Literature with Kaggle and Google Cloud Platform](https://www.kaggle.com/tentotheminus9/deep-learning-literature-and-gcp-tutorial){:target="_blank"}: This was a fun project that used GCP to run a daily script (via **cron**) that downloaded the latest deep learning literature via the National Center for Biotechnology Information (NCBI) API, extract certain bits of information, and then update a Kaggle notebook using the Kaggle API. The team over at Kaggle really liked it and asked me to blog about it  

- [Sentiment Analysis and Wordclouds](https://www.kaggle.com/tentotheminus9/sentiment-analysis-and-wordclouds){:target="_blank"}: A simple notebook using a **text-mining** package in R  

- [US Traffic Fatalities and ML Explainability](https://www.kaggle.com/tentotheminus9/us-traffic-fatalities-and-ml-explainability){:target="_blank"}: A notebook that used **BigQuery** to get data on US traffic fatalities, and then to build and explain a machine-learning model  

- [Gravity Spy Deep Learning Model](https://www.kaggle.com/tentotheminus9/gravity-spy-deep-learning-model){:target="_blank"}: A keras-based notebook that creates a simple CNN for classification of some astronomy data  

- [Data Science Through the Ages](https://www.kaggle.com/tentotheminus9/data-science-through-the-ages){:target="_blank"}: A notebook analysing some Kaggle survey data  

- [Where is Xception Looking? Grad-CAM via R](https://www.kaggle.com/tentotheminus9/where-is-xception-looking-grad-cam-via-r){:target="_blank"}: A notebook that uses **Grad-CAM** to show what parts of an images a deep learning model is using for it's decision making process  
  
<img src="/images/grad.png" alt="Grad-CAM" width="200"/>  
  
- [Linear Regression from scratch (Gradient Descent)](https://www.kaggle.com/tentotheminus9/linear-regression-from-scratch-gradient-descent): A fun notebook that creates an animation of **gradient descent** in action!  

- [Central Limit Theorem Animation](https://www.kaggle.com/tentotheminus9/central-limit-theorem-animation): Another fun notebook, showing the **central limit theorem** in action
  
#### Other

- [Leeds Cycling Dashboard](https://datamillnorth.org/products/leeds-cycling-dashboard/){:target="_blank"}: A Shiny app showing cycling incidents in the Leeds area using open-data  

- [Leeds Public Health Dashboard](https://datamillnorth.org/products/leeds-public-health-dashboard/){:target="_blank"}: A Shiny app showing mortality and disease rates in the Leeds area using open-data  

- [Live pig transports across Europe in 2013](https://robharrand.shinyapps.io/stoplivetransport_shiny/?_ga=2.60254445.112467894.1592949660-730778905.1592949660){:target="_blank"}: A Shiny app for the 'Stop Live Transport' charity campaign  

- [Visualizing Factory Farms for The Humane League's 88% campaign](https://robharrand.shinyapps.io/HumaneLeague/?_ga=2.60254445.112467894.1592949660-730778905.1592949660): A Shiny app for a Humane League charity campaign

- [House price prediction app using Python and Flask deployed on Heroku](http://houseprice2020.herokuapp.com/){:target="_blank"}: A short project that used some house price data from Kaggle to create a machine-learning model (using **random forest** and **hyperparameter tuning**), then deployed online via **Heroku** and **Flask**.