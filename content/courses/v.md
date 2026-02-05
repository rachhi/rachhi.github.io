---
title: "CSE 512: Data Visualization" 
date: 2025-09-11
url: /v/
aliases:
    - /t1.html
    - /c1/
    - /v11.html
    - /v9.html
    - /v94.html
    - /v8.html
    - /v10.html
    - /v5.html
    - /v6.html
    - /v66.html
    - /v65.html
    - /v67.html
    - /v3.html
    - /v4.html
    - /v45.html
    - /v37.html
    - /v114.html
    - /v115.html
    - /v102.html
    - /v7.html
    - /v54.html
    - /v55.html
    - /v58.html
    - /v62.html
    - /v116.html
    - /v123.html
    - /v124.html
    - /v125.html
    - /v128.html
    - /v132.html
    - /v137.html
    - /v119.html
    - /v108.html
    - /v104.html
    - /v101.html
    - /v48.html
    - /v49.html
    - /v79.html
    - /v86.html
    - /v41.html
    - /v22.html
    - /v18.html
    - /uploads/7/0/2/0/70200055/t1a.pdf
    - /uploads/7/0/2/0/70200055/t1b.pdf
    - /uploads/7/0/2/0/70200055/t1d.pdf
    - /uploads/7/0/2/0/70200055/t1f.pdf
author: "Prof: Jeffrey Heer"
description: "This course coveres effective data visualization techniques for large datasets with an emphasis on practical design using tools like D3.js, Altair, bokeh, seaborn, etc." 
summary: In this course, we developed two sample webpages for data exploration. Our goal was to create an easy-to-use " 
cover:
    image: "/v.png"
    alt: "Understanding Socioeconomic Determinants of Health"
editPost:
    URL: "https://github.com/rachhi/cse512_finalproject"
    Text: "Source for Final Project"
showToc: true
disableAnchoredHeadings: false

---

## Introduction

In our semifinal and final projects, my team chose to focus on food instability.Food stability, income disparity, and general health of the overall US population are all topics of major concern.  In this assignment, the overall question we aimed to answer is: Does our proximity to a variety of foods paired with our average income(s) affect our general health? For our interactive image webpage, we used existing datasets from 
the Rural Health Info page (https://www.ruralhealthinfo.org/), the published US Census Surveys (https://www.census.gov/programs-surveys/saipe/guidance-geographies/districts-counties.html), and from a 2020 census related to Title 1 funding (https://journalistsresource.org/economics/2020-census-title-i-maps/) to try to understand how food security relates to health outcomes across the United States. The latter dataset was also partial inspiration for the format of our maps, though the visualization we published required more data cleaning and aggregation. To that end, we compiled measures of health, socio-economic status, and goverment support; we combined datasets of diabetes prevalence, 
obesity prevalence, income measures, educational attainment, and federal government support for public schools in the county. All 
features but the school funding were already organized by county. As a proxy for federal support for school funding, we found a 
dataset of title 1 schools and school districts. The Title 1 Program provides additional federal funding support for schools where 
more than 40% of the students are low-income or below the poverty line. To add this data to our existing dataset, we summed the total 
amount of Title 1 funding per school district in a county and calculated the average amount of funding per low-income child in the county. 
Altogether, we hope this dataset can offer insight into the complex intersectionality of health outcomes, socio-economic status, and 
government support across the United States. Primary evaluation of our depicted visualization answers our intended question, 
by showing that a lower income and closer proximity to a food desert does not correlate directly to more funding in schools or 
lower obesity rates meaning residents cannot afford or get access to healthy foods needed to improve their health. 


###### Project Pages

1. [Interactive Data Visualization: Socioeconomic Determinants of Health](https://effect-of-government-subsidies-on-americans-health-451d65.pages.cs.washington.edu/)
2. [Chloropleth Visualizing Raw Data](https://health-outcomes-related-to-food-security-and-government--755033.pages.cs.washington.edu/)

###### Data Sources

Rural Health Information Hu page (https://www.ruralhealthinfo.org/), the published US Census Surveys (), and from a 2020 census related to Title 1 funding (https://journalistsresource.org/economics/2020-census-title-i-maps/)

+ [Rural Health Information Hub](https://www.ruralhealthinfo.org/) – This hub is an information clearinghouse on rural health issues, supported by the Health Resources and Services Administration (HRSA) of the U.S. Department of Health and Human Services (HHS). This resource provides open source databases on critical socioeconomic factors for rural Americans.

+ [US Census Surveys](https://www.census.gov/programs-surveys/saipe/guidance-geographies/districts-counties.html) – We use Census data to match county and state information to the cleaned data from the Rural Health Information Hub. We also compare historical records from the census to most recent data from the Rural Health Information Hub in order to clean up and sanity check our dataset.

+ [2020 Census on Title 1 Funding](https://journalistsresource.org/economics/2020-census-title-i-maps/) – We use data from this previous census on Title 1 funding. Title 1 funding is a goverment program providing financial assistance to schools with high percentages of children from low-income families. Title 1 funding seeks to help students meet challenging academic standards, funding evidence-based programs, supplemental staff, professional development, and family engagement to improve student achievement and close achievement gaps. 

