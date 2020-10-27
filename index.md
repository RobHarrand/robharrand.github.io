## Rob Harrand's GitHub Pages Website

This site gives an overview of my data science projects and completed courses.

Contact me at [tentotheminus9@gmail.com](tentotheminus9@gmail.com)  
Last update: 27th October 2020

### Public projects

#### Kaggle

I've spent many, many hours on **Kaggle** over the years, working on data-set projects, along with uploading my own collated and uploaded datasets. In fact, it was Kaggle that first introduced me to a lot of data-science concepts and tools. Here are some of my favourite mini-projects...  

  - [What Causes Heart Disease? Explaining the Model](https://www.kaggle.com/tentotheminus9/what-causes-heart-disease-explaining-the-model): A challenge set by Kaggle to create a notebook that included a machine-learning model of some sort, and then to use various tools and techniques (**purmutation importance**, **SHAP values** and **partial plots**) to explain what the model was doing. This notebook on **machine-learning interpretability** won 'kernel of the month'
  
<img src="/images/heart.png" alt="Heart disease factors" width="400"/>
  
  - [Breakthrough Listen: L-Band Data](https://www.kaggle.com/tentotheminus9/l-band-2017): My favourite hobby project to date, and one which kept me busy on many evenings and weekends. I started to look into data by SETI (the Search for Extraterrestrial Intelligence) after seeing that they'd openly shared a huge collection of datasets. I uploaded some of the data to Kaggle and created this notebook, which recreates the findings from a research paper. I also uploaded some more data and created a **deep learning** model in **keras** to classify signal types (see [here](SETI Simulated Signals - InceptionResNetV2)). Finally, I created some Python notebooks on **Google Cloud Platform** that did some novel data processing with SETI data. The files are on Github [here](https://github.com/RobHarrand/SETI_GCP)  
  
<img src="/images/seti.png" alt="SETI data" width="400"/>
  
  - [Kaggle Kernels bot mini-challenge](https://github.com/RobHarrand/kaggle-bot): A challenge set by Kaggle to create a 'bot' that does something interesting on a Kaggle dataset. I created an R script that asks the user for a dataset, creates a new notebook for it via the Kaggle API, finds a CSV file, tries to figure out which column is the target variable, removes certain columns, imputes certain values, then applies 3 machine learning models and displays a **ROC plot**  
  - [Normal vs Pneumonia - Keras in R](https://www.kaggle.com/tentotheminus9/normal-vs-pneumonia-keras-in-r): A notebook that uses keras to create a deep learning model, to tell the difference between normal and diseased radiograph images 
  
<img src="/images/xray.png" alt="ROC plot" width="300"/>
  
  - [So, You Have a Diagnostic Test Result](https://www.kaggle.com/tentotheminus9/so-you-have-a-diagnostic-test-result): A lengthy notebook detailing the statistics behind diagnostic testing  

<img src="/images/diag.png" alt="Prior to posterior probability" width="300"/>
 
  - [Deep Learning Literature with Kaggle and Google Cloud Platform](https://www.kaggle.com/tentotheminus9/deep-learning-literature-and-gcp-tutorial): This was a fun project that used GCP to run a daily script (via **cron**) that downloaded the latest deep learning literature via the National Center for Biotechnology Information (NCBI) API, extract certain bits of information, and then update a Kaggle notebook using the Kaggle API. The team over at Kaggle really liked it and asked me to blog about it  
  - [Sentiment Analysis and Wordclouds](https://www.kaggle.com/tentotheminus9/sentiment-analysis-and-wordclouds): A simple notebook using a **text-mining** package in R  
  - [US Traffic Fatalities and ML Explainability](https://www.kaggle.com/tentotheminus9/us-traffic-fatalities-and-ml-explainability): A notebook that used **BigQuery** to get data on US traffic fatalities, and then to build and explain a machine-learning model  
  - [Gravity Spy Deep Learning Model](https://www.kaggle.com/tentotheminus9/gravity-spy-deep-learning-model): A keras-based notebook that creates a simple CNN for classification of some astronomy data  
  - [Data Science Through the Ages](https://www.kaggle.com/tentotheminus9/data-science-through-the-ages): A notebook analysing some Kaggle survey data  
  - [Where is Xception Looking? Grad-CAM via R](https://www.kaggle.com/tentotheminus9/where-is-xception-looking-grad-cam-via-r): A notebook that uses **Grad-CAM** to show what parts of an images a deep learning model is using for it's decision making process  
  
<img src="/images/grad.png" alt="Grad-CAM" width="200"/>  
  
  - [Linear Regression from scratch (Gradient Descent)](https://www.kaggle.com/tentotheminus9/linear-regression-from-scratch-gradient-descent): A fun notebook that creates an animation of **gradient descent** in action!  
  - [Central Limit Theorem Animation](https://www.kaggle.com/tentotheminus9/central-limit-theorem-animation): Another fun notebook, showing the **central limit theorem** in action
  
#### Other

  - [Leeds Cycling Dashboard](https://datamillnorth.org/products/leeds-cycling-dashboard/): A Shiny app showing cycling incidents in the Leeds area using open-data  
  - [Leeds Public Health Dashboard](https://datamillnorth.org/products/leeds-public-health-dashboard/): A Shiny app showing mortality and disease rates in the Leeds area using open-data  
  - [Live pig transports across Europe in 2013](https://robharrand.shinyapps.io/stoplivetransport_shiny/?_ga=2.60254445.112467894.1592949660-730778905.1592949660): A Shiny app for the 'Stop Live Transport' charity campaign  
  - [Visualizing Factory Farms for The Humane League's 88% campaign](https://robharrand.shinyapps.io/HumaneLeague/?_ga=2.60254445.112467894.1592949660-730778905.1592949660): A Shiny app for a Humane League charity campaign
  - [House price prediction app using Python and Flask deployed on Heroku](http://houseprice2020.herokuapp.com/): A short project that used some house price data from Kaggle to create a machine-learning model (using **random forest** and **hyperparameter tuning**), then deployed online via **Heroku** and **Flask**.

### Work projects

- Implementing **data management** and **data quality** standard operating procedures: This is an ongoing piece of work, improving the overall data maturity of the company. This is being done by improving systems and processes, and the data literacy of staff  
- Designing new, streamlined workflows, combined with data cleaning of old financial and CRM system databases: Lots of legacy systems that needed a lot of cleaning up. This has been done (and continues to be done) using R and Python scripts  
- Developing **machine-learning models** for disease diagnosis: Pretty simple but interesting models using veterinary blood biomarkers and a few clinical signs. These were for dogs and cats, classifying diseased pets into different possible disease categories  
- Prototyping **deep-learning models** for disease detection in canine chest X-rays: A proof-of-concept project applying deep learning models to veterinary X-rays (DICOM image format). Models were created and evaluated using keras in Pythons, but data quality was unfortunately too poor to take things further. A handful of CT-scans were also explored via Python  
-	Helped to inform the company's international strategy using analysis of open datasets: A small but interesting peice of work bringing together multiple open-source datasets to try and give some evidence behind which parts of the world to target for international sales/R&D  
- Statistical analysis and data visualisation on equine allergy paper titled ["Co‐reactivity between related and unrelated environmental allergens in equine allergen‐specific IgE serology testing in the UK."](https://onlinelibrary.wiley.com/doi/abs/10.1111/vde.12786): A really interesting study that involved calculating odds ratios between multiple blood-marker measurements, along with some nice correlations plots in R  
- Aiding scientists in the statistical design of experiments, including **power calculations**, data management planning, avoiding bias, etc.: Ad hoc support across the company  
- Aiding in the interpretation of diagnostic tests results using **Bayesian priors** and **likelihood ratios**: A lot of diagnostic testing seems to be reduced to quoting sensitivity and specificity for a given test. Using Bayesian statistics, such measures were put into a more realistic setting using prior probabilities based upon clinical signs  
- Using data-driven marketing techniques such as **RFM segmentation** and **clustering** of customers, combined with reporting **dashboards**, to direct the company’s sales team: This project took the existing approach to sales from being largely instinct-driven to using data and evidence. A R Shiny app was created, that automatically pulled sales data from the companies Sage system via SQL commands, preprocessed it, and displayed sales on an interactive map. Each point was classified and colour-coded by RFM (Recency, Frequency, Monetary value) segment, which were determined using **k-means** clustering. The app also generated tables, reports and PowerPoint slides, and included metrics such as **customer lifetime value** to arm the sales team with all the information they required to plan their diaries. This RFM work also informed the company marketing strategy, which up until this point had involved sending the same message to all customers  
- Formal data exploration, analysis and communication via **coding notebooks** for major company projects and external collaborations: Previously, all data and results for collaborations or CRO work were shared via Excel spreadsheets. I began to also send R notebooks in order to make our analysis reproducible and transparent  
- Developing **Shiny apps** to provide tools across the company, including routine lab test results monitoring, financial reporting dashboards and automated scientific data analysis, curve fitting and outlier detection: These apps were created for two main reasons. First, to reduce the amount of manual analysis and/or subjective decision making that was needed across the company. Second, to reduce the scope for error  
- Designing and implementing an **SQL database** to store Next Generation Sequencing (NGS) data, combined with a front-end to allow non-technical members of staff to query the underlying data: A large project using a Shiny app and a mySQL database to store data and utilise complex nucleotide data. I later recreated it in asp.net  
- Designing and teaching data-science workshops to staff members, following the structure of **[Data Carpentry](https://carpentries-incubator.github.io/life-sciences-workshop/)** lessons: A major piece of work creating and then teaching data science material to company staff  
- Conducting a group-wide **data audit** with the heads of all teams (scientific and financial), developing a **data strategy** for the company to improve efficieny and reduce costs:  A project that kick-started a continuous area of process improvement work, and focussing attentional on the data-related business requirements for the company  
- Leading the customer-side on the development of a Laboratory Information Management System (LIMS) in conjunction with the company IT department (working in an **Agile** framework):  Working with IT to create this system, focussing on user requirements. I also used R and Python scripts to allow calculations to be done outside of the LIMS, expanding its capabilities  
- Mentoring R&D staff on their general work and project planning, with a focus on data analysis: Improving the R&D team's use of data overall  
- At the time of writing, I am working on some Next Generation Sequencing data analysis using **Spark** on **AWS**  

### Blog posts

Several of the posts below have been picked up by the 'Towards Data Science' team on Medium,

#### 2020

- [COVID-19 Testing. What are your chances?](https://towardsdatascience.com/covid-19-testing-what-are-your-chances-33f0af5d2ae4)
- [Is Data Science For You?](https://towardsdatascience.com/is-data-science-for-you-6cbe995ad349)
- [Animal Rights Across the Globe — The Numbers](https://medium.com/@tentotheminus9/animal-rights-across-the-globe-the-numbers-cdc84993da2b)
- [Applying Data Science](https://towardsdatascience.com/applying-data-science-8b5d3a332d8c)

#### 2019

- [Understanding Veterinary Papers — A Data and Statistics Perspective (Part 5)](https://medium.com/@tentotheminus9/understanding-veterinary-papers-a-data-and-statistics-perspective-part-5-e9eb93e36790)
- [Understanding Veterinary Papers — A Data and Statistics Perspective (Part 4)](https://medium.com/@tentotheminus9/understanding-veterinary-papers-a-data-and-statistics-perspective-part-4-daf21d1b4abd)
- [Understanding Veterinary Papers — A Data and Statistics Perspective (Part 3)](https://medium.com/@tentotheminus9/understanding-veterinary-papers-a-data-and-statistics-perspective-part-3-2896238e2b8e)
- [Understanding Veterinary Papers — A Data and Statistics Perspective (Part 2)](https://medium.com/@tentotheminus9/understanding-veterinary-papers-a-data-and-statistics-perspective-part-2-e3e042039818)
- [Understanding Veterinary Papers — A Data and Statistics Perspective (Part 1)](https://medium.com/@tentotheminus9/understanding-veterinary-papers-a-data-and-statistics-perspective-part-1-365a2b16415f)
- [Searching for ET using AI on GCP](https://towardsdatascience.com/searching-for-et-using-ai-on-gcp-b45b07ba5b6)
- [Deep Learning Literature with Kaggle and Google Cloud Platform](https://towardsdatascience.com/deep-learning-literature-with-kaggle-and-google-cloud-platform-6d7d93d14997)

#### 2018

- [Breathing Britain](https://medium.com/@tentotheminus9/breathing-britain-c7f62983e1c6)
- [To Sneeze or Not to Sneeze](https://medium.com/@tentotheminus9/to-sneeze-or-not-to-sneeze-11a2e36dfe89)
- [Veterinary Stats — Reference Intervals](https://medium.com/@tentotheminus9/veterinary-stats-reference-intervals-765ac7656d1)
- [Veterinary Stats 2: The Central Limit Theorem; A Crisis of Confidence](https://medium.com/@tentotheminus9/veterinary-stats-2-the-central-limit-theorem-a-crisis-of-confidence-ff78466bb898)
- [Veterinary Stats 1: Laying the Foundations](https://medium.com/@tentotheminus9/veterinary-stats-1-laying-the-foundations-c1ac6300166e)
- [Veterinary Data: Twitter Scraping](https://medium.com/@tentotheminus9/veterinary-data-twitter-scraping-b0d3e6f5f36b)
- [Veterinary Data: Machine Learning](https://medium.com/@tentotheminus9/veterinary-data-machine-learning-dd92379f4359)
- [So, You Have a Diagnostic Test Result](https://medium.com/@tentotheminus9/so-you-have-a-diagnostic-test-result-6f45a182d1c4)

#### 2017

- [Veterinary Data: Tools of the Trade (Part 2 of 2)](https://medium.com/@tentotheminus9/veterinary-data-tools-of-the-trade-part-2-of-2-5ff3050665ec)
- [Veterinary Data: Tools of the Trade (Part 1 of 2)](https://medium.com/@tentotheminus9/veterinary-data-tools-of-the-trade-part-1-of-2-bb468457c4fd)
- [Veterinary Data: Animal Data Abound!](https://towardsdatascience.com/data-in-veterinary-animal-data-abound-8d8ba92bbdbc)
- [The Genesis of Data Science](https://towardsdatascience.com/the-genesis-of-data-science-fd86c6c8b6b3)
- [Veterinary Data: Open Sesame!](https://medium.com/@tentotheminus9/veterinary-data-open-sesame-92aa5fd6a91b)
- [Veterinary Data: Mining the Archives](https://medium.com/@tentotheminus9/data-in-veterinary-mining-the-archives-ce2a4b5f35d4)
- [Veterinary Data: Your Untapped Commodity](https://towardsdatascience.com/data-in-veterinary-your-untapped-commodity-1d6ac67c3d5e)

### Self-learning courses completed

I have always enjoyed data science courses, and have tended to alternate between courses and projects (working on projects after a few courses, to cement the concepts that I had just covered). Many of the below courses also involved project work.

- **The Data Scientist’s Toolbox** – Coursera - Nov 2015
- **R Programming** – Coursera – Nov 2015
- **Getting and Cleaning Data** – Coursera – Nov 2015
- **Exploratory Data Analysis** – Coursera – Nov 2015
- **Reproducible Research** – Coursera – Nov 2015
- **Statistical Inference** - Coursera – Nov 2015
- **Regression Models** – Coursera – Jan 2016
- **Practical Machine Learning** – Coursera – Jan 2016
- **Developing Data Products** – Coursera – Jan 2016
- **Taming Big Data with MapReduce and Hadoop** – Udemy – Jan 2016
- **Python Step by Step: Build a Data Analysis Program** – Udemy – Jan 2016
- **Practical SQL Skills** – Udemy – Jan 2016
- **Hadoop Starter Kit** – Udemy – Jan 2016
- **Data Science Capstone** – Coursera – April 2016
- **R for Big Data** – Newcastle University – June 2016
- **Machine Learning** – Coursera – June 2016
- **Workshop in Probability and Statistics** – Udemy – June 2016
- **Supercharge R with SparkR** – Udemy - June 2016
- **Time Series Analysis and Forecasting in R** – July 2016
- **Bayesian Statistics** – Coursera - August 2016
- **Managing Big Data with MySQL** – Coursera – August 2016
- **Numpy stack** – Udemy – Feb 2017
- **Javascript Basics** – Udacity – March 2017
- **Data Visualisation and D3js** – Udacity – March 2017
- **Big Data and Social Analytics** – MIT Experimental Learning – March 2017
- **Python Beyond the Basics** - Object-Oriented Programming – Udemy – April 2017
- **Linear Algebra Refresher** – Udacity – May 2017
- **Research Data Management and Sharing** – Coursera – May 2017
- **Agile and Scrum Bootcamp** – Udemy – June 2017
- **Big Data with Hadoop and Spark** – CloudxLab – June 2017
- **Neural Networks and Deep Learning** – Coursera – December 2017
- **Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization** – Coursera – January 2018
- **Structuring Machine Learning Projects** – January 2018
- **Convolutional Neural Networks** – February 2018
- **Data science ethics** – February 2018
- **Sequence models** – March 2018
- **Tableau 10: Practical and Concise** – Udemy, July 2018
- **A Crash Course in Data Science** – June 2018
- **Building a Data Science Team** – June 2018
- **Managing Data Analysis** – July 2018
- **Data Science in Real Life** – July 2018
- **Executive Data Science Capstone** – July 2018
- **The Unix Workbench** – July 2018
- **Google Cloud Platform Big Data and Machine Learning Fundamentals** – January 2019
- **Leveraging Unstructured Data with Cloud Dataproc on Google Cloud Platform** – January 2019
- **Serverless Data Analysis with Google BigQuery and Cloud Dataflow** – January 2019
- **Serverless Machine Learning with Tensorflow on Google Cloud Platform** – February 2019
- **Building Resilient Streaming Systems on Google Cloud Platform** – March 2019
- **Machine Learning Explainability** – Kaggle Learn – May 2019
- **Foundations of strategic business analytics** – July 2019
- **Foundations of marketing analytics** – July 2019
- **Case studies in business analytics with ACCENTURE** – August 2019
- **Capstone: Create Value from Open Data** – September 2019
- **The Manager's Toolkit: A Practical Guide to Managing People at Work** – September 2019
- **Data quality fundamentals** – Feb 2020 (Udemy)
- **Big Data, Genes and Medicine** – Feb 2020 (Coursera)
- **Improving your Statistical Inferences** – May 2020 (Coursera)
- **Improving your Statistical Questions** – May 2020 (Coursera)
- **ISO 13485:2016 for Medical Device Development and QMS** - October 2020 (Udemy)
- **Data Governance Fundamentals** - October 2020 (Udemy)

-	Regular attendance at a monthly Leeds **data-science meetup**

### Formal education

- PhD Physics, University of Leeds (2007)
- MSc Nanoscale Science & Technology, University of Leeds (2004)
- BSc Physics with Astrophysics, University of York (2001)
