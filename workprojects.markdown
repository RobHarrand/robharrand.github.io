---
layout: page
title: Work Projects
permalink: /workprojects/
---

## Work Projects

- Implementing **data management** and **data quality** standard operating procedures: This is an ongoing piece of work, improving the overall data maturity of the company. This is being done by improving systems and processes, and the data literacy of staff  

- Designing new, streamlined workflows, combined with data cleaning of old financial and CRM system databases: Lots of legacy systems that needed a lot of cleaning up. This has been done (and continues to be done) using R and Python scripts  

- Developing **machine-learning models** for disease diagnosis: Pretty simple but interesting models using veterinary blood biomarkers and a few clinical signs. These were for dogs and cats, classifying diseased pets into different possible disease categories

- Prototyping **deep-learning models** for disease detection in canine chest X-rays: A proof-of-concept project applying deep learning models to veterinary X-rays (DICOM image format). Models were created and evaluated using keras in Pythons, but data quality was unfortunately too poor to take things further. A handful of CT-scans were also explored via Python

<img src="/images/dog_ct.jpg" alt="Dog CT scan (bone only)" width="300"/>

-	Helped to inform the company's international strategy using analysis of open datasets: A small but interesting peice of work bringing together multiple open-source datasets to try and give some evidence behind which parts of the world to target for international sales/R&D  

- Statistical analysis and data visualisation on equine allergy paper titled ["Co-reactivity between related and unrelated environmental allergens in equine allergen-specific IgE serology testing in the UK."](https://onlinelibrary.wiley.com/doi/abs/10.1111/vde.12786){:target="_blank"}: An interesting study that involved calculating odds ratios between multiple blood-marker measurements, along with some nice correlations plots in R  

- Aiding scientists in the statistical design of experiments, including **power calculations**, data management planning, avoiding bias, etc.: Ad hoc support across the company  

- Aiding in the interpretation of diagnostic tests results using **Bayesian priors** and **likelihood ratios**: A lot of diagnostic testing seems to be reduced to quoting sensitivity and specificity for a given test. Using Bayesian statistics, such measures were put into a more realistic setting using prior probabilities based upon clinical signs  

- Using data-driven marketing techniques such as **RFM segmentation** and **clustering** of customers, combined with reporting **dashboards**, to direct the company's sales team: This project took the existing approach to sales from being largely instinct-driven to using data and evidence. A R Shiny app was created, that automatically pulled sales data from the companies Sage system via SQL commands, preprocessed it, and displayed sales on an interactive map. Each point was classified and colour-coded by RFM (Recency, Frequency, Monetary value) segment, which were determined using **k-means** clustering. The app also generated tables, reports and PowerPoint slides, and included metrics such as **customer lifetime value** to arm the sales team with all the information they required to plan their diaries. This RFM work also informed the company marketing strategy, which up until this point had involved sending the same message to all customers  

- Formal data exploration, analysis and communication via **coding notebooks** for major company projects and external collaborations: Previously, all data and results for collaborations or CRO work were shared via Excel spreadsheets. I began to also send R notebooks in order to make our analysis reproducible and transparent  

- Developing **Shiny apps** to provide tools across the company, including routine lab test results monitoring, financial reporting dashboards and automated scientific data analysis, curve fitting and outlier detection: These apps were created for two main reasons. First, to reduce the amount of manual analysis and/or subjective decision making that was needed across the company. Second, to reduce the scope for error  

- Designing and implementing an **SQL database** to store Next Generation Sequencing (NGS) data, combined with a front-end to allow non-technical members of staff to query the underlying data: A large project using a Shiny app and a mySQL database to store data and utilise complex nucleotide data. I later recreated it in asp.net  

- Designing and teaching data-science workshops to staff members, following the structure of **[Data Carpentry](https://carpentries-incubator.github.io/life-sciences-workshop/){:target="_blank"}** lessons: A major piece of work creating and then teaching data science material to company staff  

- Conducting a group-wide **data audit** with the heads of all teams (scientific and financial), developing a **data strategy** for the company to improve efficieny and reduce costs:  A project that kick-started a continuous area of process improvement work, and focussing attentional on the data-related business requirements for the company  

- Leading the customer-side on the development of a Laboratory Information Management System (LIMS) in conjunction with the company IT department (working in an **Agile** framework):  Working with IT to create this system, focussing on user requirements. I also used R and Python scripts to allow calculations to be done outside of the LIMS, expanding its capabilities  

- Mentoring R&D staff on their general work and project planning, with a focus on data analysis: Improving the R&D team's use of data overall  

- At the time of writing, I am working on some Next Generation Sequencing data analysis using **Spark** on **AWS**  