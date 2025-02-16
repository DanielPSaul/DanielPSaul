<h1 align="center">Hi 👋, I'm Daniel!</h1>

<br>

# Introduction 🤝
Hello! My name is Daniel Saul, and currently, I am a Business Operations Engineer at intelliflo and a graduate of the Master of Science in Business Analytics (MSBA) program at the University of Georgia (UGA). I am originally from Nashville, Tennessee, but I spent the prior 4 years in Athens at UGA completing my Bachelor of Business Administration in Management Information Systems (MIS) with an Area of Emphasis in Data Analytics. I love the creative abilities data and technology has to offer, and I enjoy partaking in personal projects to help myself expand my knowledge and grow! Feel free to connect with me on
  <a href="https://www.linkedin.com/in/danielsaul1/" rel="nofollow noreferrer">
    <img src="https://i.sstatic.net/gVE0j.png" alt="linkedin"> LinkedIn
  </a> or reach out!

<br>

# Portfolio Contents 🗂️
This repository consists of work completed through technical personal projects, part-time experiences, and coursework. Some code, projects, or files may be limited due to lost items or the prevention of releasing personal or sensitive data/information.

<br>

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=danielpsaul&show_icons=true&locale=en&layout=compact" alt="danielpsaul" /></p>

<br>

* [Web Application Development](https://github.com/DanielPSaul#web-application-development)
    * [Solar Panel Simulation](https://github.com/DanielPSaul#solar-panel-simulation)
    * [Solar Panel Optimizaton](https://github.com/DanielPSaul#solar-panel-optimization)
    * [Perovskite LCOE Calculator](https://github.com/DanielPSaul#perovskite-lcoe-calculator)
    * [UGA Baseball Heat Maps](https://github.com/DanielPSaul#uga-baseball-heat-maps)
    * [Donut Shop Website](https://github.com/DanielPSaul#donut-shop-website)
    * [Food Blog Website](https://github.com/DanielPSaul#food-blog-website)
    * [Clothing Shop App](https://github.com/DanielPSaul#clothing-shop-app)
    * [Loan Amortization App](https://github.com/DanielPSaul#loan-amortization-app)
    * [Book Database](https://github.com/DanielPSaul#book-database)
* [Data Science & Analytics](https://github.com/DanielPSaul#data-science-&-analytics)
    * [GameStop Case Study](https://github.com/DanielPSaul#gamestop-case-study)
    * [March Madness Prediction](https://github.com/DanielPSaul#march-madness-prediction)
    * [Fitness App Business Problem](https://github.com/DanielPSaul#fitness-app-business-problem)
    * [Marketing Analytics Collection](https://github.com/DanielPSaul#marketing-analytics-collection)
    * [Machine Learning Collection](https://github.com/DanielPSaul#machine-learning-collection)
    * [Energy Informatics Collection](https://github.com/DanielPSaul#energy-informatics-collection)
    * [National Football League Arrests](https://github.com/DanielPSaul#national-football-league-arrests)
    * [Online Marketplace Price Prediction](https://github.com/DanielPSaul#online-marketplace-price-prediction)
    * [My Job Application Process](https://github.com/DanielPSaul#my-job-application-process-2022)
    * [Economic Time Series](https://github.com/DanielPSaul#economic-time-series)
    * [Data Management Collection](https://github.com/DanielPSaul#data-management-collection)
 
### Other Notable Projects (not in portfolio)
* Delta Air Lines Fuel Forecasting Capstone Project
* UGA Student Organizations Salesforce System
* Health Insurance System Business Process Management Notation Mapping



<br>
  
## Web Application Development  
### Solar Panel Simulation
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/SolarPanelApp)
[![](https://img.shields.io/badge/ShinyApps.io-Open_Web_App-3686d3?logo=r)](https://daniel-saul.shinyapps.io/Solar-Panel-Simulation/)

**Concepts:** Interactive Web App Development, API's, Data Transformation, Data Analytics, Data Visualization

**Software & Languages:** R, System Advisor Model (SAM), PVWatts

**Packages:** shiny, rsconnect, shinythemes, shinydashboard, DT, tidyverse, shinyalert, shinyBS, shinyjs, leaflet, zipcodeR, plotly, lubridate, httr, reshape2, writexl, xlsx, readxl

**Description:** With this solar panel simulation application, users can enter zipcode, solar panel/system, and financial inputs to run a simulation that provides analysis of energy and financial outputs based on a certain location's weather data. The weather data used is a typical meteorological year (TMY) file which represents the average weather conditions over a select year range. It is extracted from the National Solar Radiation Database (NSRDB) and run through the National Renewable Energy Laboratory (NREL) SAM model. Outputs are visualized through plots and tables at an annual, monthly, and hourly basis. This project is one of the apps developled during my student assistantship with the Terry College of Business - Management Information Systems and Physics department at the University of Georgia.

<br>

### Solar Panel Optimization
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/SolarPanelOpt)
[![](https://img.shields.io/badge/ShinyApps.io-Open_Web_App-3686d3?logo=r)](https://daniel-saul.shinyapps.io/Solar-Panel-LP/)

**Concepts:** Interactive Web App Development, Linear Programming

**Software & Languages:** R

**Packages:** shiny, rsconnect, tidyverse, lpSolve, shinythemes, shinydashboard, DT, shinyalert, shinyjs, shinyBS, rmarkdown, xlsx, readxl, writexl

**Description:** With this simple solar panel optimization calculator, users enter an anlysis period, panel, electricity, and demand inputs then outputs the total cost of the solar project, optimal number of panels, and purchased kWh per analysis year for greenhouse applications. The results can be adjusted based on new panel energy generatiion and downloaded to an Excel file. This project is one of the apps developled during my student assistantship with the Terry College of Business - Management Information Systems and Physics department at the University of Georgia.

<br>

### Perovskite LCOE Calculator
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/PerovskiteCalc)
[![](https://img.shields.io/badge/ShinyApps.io-Open_Web_App-3686d3?logo=r)](https://daniel-saul.shinyapps.io/Perovskite-App/)

**Concepts:** Interactive Web App Development, Data Analytics, Data Visualization, API's 

**Software & Languages:** R, PVWatts

**Packages:** shiny, rsconnect, shinythemes, shinydashboard, DT, tidyverse, shinyalert, shinyBS, shinyjs, leaflet, zipcodeR, plotly, lubridate, httr, reshape2, writexl, xlsx, readxl

**Description:** With this simple perovskite solar panel project cost calculator, users enter location and various levelized cost of electricity (LCOE) inputs such as total installation cost, discount rate, and annual panel energy generated. Then, a basic table and visualizations, which are downloadable, are outputted with the overall calculated LCOE compared to local commercial, industrial, and residential eletricity prices offered by the local power company. Users can also select to enter an LCOE value they already have and simply compare to the electricity rates. This project is one of the apps developled during my student assistantship with the Terry College of Business - Management Information Systems and Physics department at the University of Georgia. Specifically, requirements were gathered from the Physics Department at UGA for perovskite solar cells they are developing.

<br>

### UGA Baseball Heatmaps
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/BaseballHeatmaps)

**Concepts:** Interactive Web App Development, Data Transformation, Data Analytics, Data Visualization, Sports Analytics

**Software & Languages:** R

**Packages:** shiny, tidyverse, plotly

**Description:** This web application was built for the University of Georgia baseball team's pitchers and pitching coaches to help analyze pitching and opposing players batting habits and win more games. It resulted from a semester-long project for a sports analytics directed study elective completed during my first semester in the MSBA. My team and I were tasked with building less clunky and smooth heat maps based on pitching location within a strike zone combined with the outcome of the pitch. The application has been built in iterations by previous groups, so we were responsible for creating two tabs, pitching and hitting heat maps, along with various other baseball-related statistics in the visuals. Users can input the season, game or range of games, batter side, pitch types, pitch outcomes, and pitcher in which faceted heat maps and a statistics table are generated. Inputs are similar for the batting analysis, except that the heat maps display the pitch location pitched to the opposing batter, faceted by the outcome of the pitch instead of the pitch type. Sample photos and the select code we created are included in the repository as well as the full app code.

<br>

### Donut Shop Website
[![Wix](https://img.shields.io/badge/wix-000?style=for-the-badge&logo=wix&logoColor=white)](https://danielsaul.wixsite.com/donutworry)
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/DonutShopWebsite)

**Concepts:** Cloud-Based Web App Development, Project Management

**Software & Languages:** Wix.com

**Packages:** N/A

**Description:** This website was built with the cloud-based website service, Wix.com, for a project management course group project at UGA. The capstone project required that each group selects a local business with a feasible problem we solve using technology and the project manangement lifecycle. We decided to build an interactive website for a donut shop located in Lawrenceville, Georgia because they were struggling with customer engagement and online orders due to the pandemic and its only consumer communication source being a Facebook page. The webpage is equiped with online ordering capabilities, general store information such as hours and history, menus, product photo galleries, social media links, company news, contact form functionality, and more.

<br>

### Food Blog Website
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/FoodBlogWebsite)

**Concepts:** Network Applications, Static Web Development

**Software & Languages:** Apache Tomcat, HTML, CSS, Eclipse, Java

**Packages:** N/A

**Description:** This basic website was a project I worked on and created in a network application and web development course at UGA. We were tasked with building static website based on minimal visual requirements. It is modeled from a food blog Instagram page I currently operate. It includes recipes, pictures, tips, and contact information. I have included a sample photo of the home page, but I recommend opening the index.html file to explore the site.

<br>

### Clothing Shop App
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/ClothingShopApp)

**Concepts:** Application Development, Object-Oriented Programming Principles, System Process Management

**Software & Languages:** Java, Eclipse

**Packages:** N/A

**Description:** This report was a group project I worked on in a business programming course at UGA. We were tasked with creating an inventory database and system for a hypothetical online shopping system of our choosing. We decided to create a system for an online clothing store called "Custom Clothing Athens." We included scenario flowcharts, demonstrations, and UML diagrams. It covers the data types: Arrays, ArrayLists, HashSets, and HashMaps. The project also covers the object-oriented programming principles Inheritance, Encapsulation, and Polymorphism. Since this project focused more on the server side and not the user interface, I have included the code and my group's presentation report which will help the viewer visualize the project.

<br>

### Loan Amortization App
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/LoanAmortApp)

**Concepts:** Cloud Network Applications, Dynamic Web Development

**Software & Languages:** Apache Tomcat, HTML, CSS, Eclipse, Java, AWS

**Packages:** N/A

**Description:** This basic website was an assignment I worked on and created in a cloud network application and web development course at UGA. We were tasked with building a dynamic website mimicing a loan amortization calculator. It takes the inputs of loan principal, term, and rate. The app then displays a loan amortization table output over time. We used AWS S3 for cloud storage and other AWS products such as EC2, Elastic Beanstalk, AWS Console, and RDS. I have included this project in my portfolio to get a glimpse of my past experiences with web development, but unfortunately, I have lost the correct software and connections to run and visualize the app.

<br>

### Book Database
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/BookDatabase)

**Concepts:** Cloud Network Applications, Dynamic Web Development

**Software & Languages:** Apache Tomcat, HTML, CSS, Eclipse, Java, AWS

**Packages:** N/A

**Description:** This basic website was an assignment I worked on and created in a cloud network application and web development course at UGA. We were tasked with building a dynamic website mimicing a book database or online library. We used AWS S3 for cloud storage and other AWS products such as EC2, Elastic Beanstalk, AWS Console, and RDS It shows all of the books available in the database, giving to the option to add, edit, or delete books. I have included this project in my portfolio to get a glimpse of my past experiences with web development, but unfortunately, I have lost the correct software and connections to run and visualize the app.

<br>





## Data Science & Analytics
### GameStop Case Study
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/GameStopCaseStudy)

**Concepts:** Data Visualization, Web Scraping, Data Analysis, Data Wrangling, Data Transformation

**Software & Languages:** Tableau, R

**Packages:** tidyverse, xml2, tibble, rvest

**Description:** This case study was conducted as part of my midterm exam requirement for a Business Intelligence course I took at UGA. We were tasked with web scraping video game data from OpenCritic, a video game critic blog, and making video game sale strategy recommendations for GameStop. Web scraping was done with R and the descriptive visualizations were created in Tableau to help further enhance my analysis. The web scraping code and full report are included in the repository.

<br>

### March Madness Prediction
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/MarchMadnessPrediction)

**Concepts:** Machine Learning, Data Visualization, Data Analysis

**Software & Languages:** Tableau, R

**Packages:** tidyverse, rvest, caret, dbplyer, corrplot

**Description:** This report was conducted as part of a group project for a Business Intelligence course I took at UGA. My group and I were tasked with picking any current topic and making a prediction of some sort with it. Every spring, the popular Men's NCAA March Madness basketball tournament is played and millions of fans create brackets and compete to see who can predict a winner. Our group decided it was the perfect time to attempt to predict a March Madness winner with machine learning methods. We sourced our data from Kaggle, created descriptive visualizations with Tableau, and made a traditional OLS regression model with R running repeatedly to predict the most tournament wins. We trained the model on data from the 2015 - 2019 seasons and tested the model on the 2021 season. Our model yielded 34% more points than the average bracket and has a meaningful impact on bracket performance as a result.

<br>

### Fitness App Business Problem
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/FitnessAppBusinessProblem)

**Concepts:** Relational Database Management, Data Management

**Software & Languages:** SQL, MySQL

**Packages:** N/A

**Description:** This project was conducted as a group for a Data Management and Analytics course I took at UGA. It was actually the first coding class I ever took, so please bare with me. My group was tasked with finding a real technology problem for a company, building a database and queries to help fix part of the issues, and make recommendations on what to do next. We decided to create new hypothetical subscription plans for FitBit: one being a sleep database and tracker, and the second being recommendations generated for a user with the "original" database. I do not have access to the database anymore, but I did include the SQL queries in a file included in the repository. The report displays the business problem, queries and outputs, data dictionaries, and database model.

<br>

### Marketing Analytics Collection
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/MarketingAnalyticsCollection)

**Concepts:** Marketing Analytics, Statistics, Data Visualization, Machine Learning

**Software & Languages:** Tableau, SPSS

**Packages:** N/A

**Description:** This repository holds a collection of multiple assignments and projects I completed for a Marketing Analytics and Prediction course I took at UGA. Most of our work was done using the statistical software SPSS and data vizualization software Tableau. There is a mix of casino, retail, and online shopping analysis. Additionally, I performed a decent amount of machine learning with marketing data; specifically using decision trees, RFM, multiple linear regression, and logistic regression.

<br>

### Machine Learning Collection
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/MachineLearningCollection)

**Concepts:** Machine Learning, Data Visualization, Time Series Analysis, Forecasting, Data Transformation and Wrangling, Natural Language Processing, API's

**Software & Languages:** Python, Jupyter Notebook

**Packages:** pandas, numpy, matplotlib, seaborn, datetime, yfinance, sklearn, bs4, requests, json, tqdm, pygments, google_play_scraper, eli5, nltk

**Description:** This repository holds a collection of multiple assignments that were not large enough for their own repository I completed for a Machine Learning course at UGA. There is a mix of machine learning methodologies and large amount of data cleansing. The assignments feature working with the FRED API to gather S&P500 and financial data, banking and loan default status, NYSE and the affects of world events and synthetic data, the CAPM and COVID analysis, and Amazon app reviews. The bulk of the machine learning concepts I used were linear regression, classification, PCA analysis, sentiment analysis, and Random Forest models.

<br>

### Energy Informatics Collection
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/EnergyInformaticsCollection)

**Concepts:** Statistics, Sustainability, Renewable Energy Analysis, Time Series Analysis, Data Transformation and Wrangling, Linear Regression, Optimization and Prescriptive Analytics

**Software & Languages:** RStudio, Markdown, R

**Packages:** tidyverse, lubridate, tinytex, gt, dygraphs, xts, eia, EIAdata, lpSolveAPI, TSP, ggmap, mapproj, measurements, googleway

**Description:** This repository holds a collection of multiple pair assignments that were not large enough for their own repository I completed for a Energy Informatics course at UGA. The code utilizes R and Markdown to clean and present data that represents various sustainable methods in energy informatics. We dealt with weather and radiation data to calculate energy generated over time, temperature and renewable energy analysis over time, and crop production and supply chain efficiency. I have also included a small group presentation to display the content we were working with in visual sense.

<br>

### NFL Arrests
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/NFLArrests)

**Concepts:** Data Visualization, Data Analysis

**Software & Languages:** Tableau

**Packages:** N/A

**Description:** This is a basic personal project I completed in Tableau that analyzes details of NFL player arrests over the period of 2000 to 2017. The visuals are split by incidents over time, total incidents by team, total incidents by charge category, and total incidents by each position.

<br>

### Online Marketplace Price Prediction
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/OnlineMarketplacePricePrediction)

**Concepts:** Data Visualization, Data Analysis, Sentiment Analysis, Machine Learning

**Software & Languages:** Python, Jupyter Notebook

**Packages:** pandas, numpy, matplotlib, seaborn, plotly, nltk, sklearn, 

**Description:** This was the final group project in my Machine Learning course I took during the MSBA program. The purpose of this report is to dive into the data provided by a seller, create an accurate model using machine learning methodologies, and predict the price of a specific product in an online marketplace where buyers and sellers can come together to trade goods and services. The code is included in a Jupyter Notebook and a PDF of the report as well.

<br>

### My Job Application Process (2022)
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/MyJobApplicationProcess)

**Concepts:** Data Visualization, Data Analysis, Data Collection, Data Cleaning

**Software & Languages:** Python, Jupyter Notebook

**Packages:** pandas, numpy, seaborn, datetime, matplotlib

**Description:** This was a personal project I completed for practice purposes after receiving and accepting a job offer during the MSBA program recruitment cycle. I was interested to understand the details of positions I applied to over time. I kept logs of each application I submitted in a Google Sheet which I then converted to a CSV file for the project. The data needed to be manipulated to add value to the visualizations. The notebook and job application dashboard are included in the repository.

<br>

### Economic Time Series
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/EconomicTimeSeries)

**Concepts:** Data Visualization, Data Analysis, Time Series Analysis, Machine Learning

**Software & Languages:** Python, Jupyter Notebook, Microsoft Office

**Packages:** pandas, numpy, altair, matplotlib, requests, tabulate statsmodels

**Description:** This project was a simple exercise in using univariate time series models on time series data to estimate
causal effects and to forecast future values in my graduate Economic Time Series course. We were given the option to choose a topic to conduct our analysis on in which I chose the effect of increasing temperatures on housing prices in the United States. The temperature data was sourced from from the National Centers for Environmental Information (NCEI) within the National Oceanic and Atmospheric Administration (NOAA) and housing price data from the FRED database. My findings determined that the causal effect is significant and the forecasted values display an increase in the relationship of both climate change and housing costs.

<br>

### Data Management Collection
[![](https://img.shields.io/badge/GitHub-View_on_GitHub-6e5494?logo=GitHub)](https://github.com/DanielPSaul/DataManagementCollection)

**Concepts:** Data Management, Data Analysis, Data Visualization, API's, Network Analysis, Data Wrangling

**Software & Languages:** Python, Jupyter Notebook

**Packages:** numpy, pandas, altair, networkx, requests

**Description:** This repository holds a collection of multiple group assignments that were not large enough for their own repository I completed for a Advanced Data Management and Analytics course at UGA. Each one becomes more advanced as the course went on, using sample datasets to answer specfic questions given by our professor that ultimately rely on each other to solve. Each assignment also addresses different chunks of concepts we were learning in the course.

<br>

