# 7. A/B Testing at WorldQuant University

## Project Overview

This project focuses on experimental design and statistical hypothesis testing. The objective is to determine whether sending an email increases program enrollment at WorldQuant University using data from a controlled A/B experiment.

The project combines statistical analysis, software engineering, database management, and interactive dashboard development to build a complete data application around an experimental study.

## Skills Demonstrated

* Experimental Design
* A/B Testing
* Statistical Hypothesis Testing
* Chi-Square Testing
* Odds Ratio Analysis
* Data Wrangling
* MongoDB Data Extraction
* Object-Oriented Programming (OOP)
* ETL Pipeline Development
* Interactive Dashboard Design
* Three-Tier Software Architecture

## Learning Outcomes

Throughout this project, I learned how to:

* Retrieve experimental data from MongoDB using PyMongo
* Build custom Python classes for ETL processes
* Design reusable and scalable OOP solutions
* Create contingency tables through data wrangling and cross-tabulation
* Calculate odds ratios to measure treatment effects
* Perform Chi-Square tests using Statsmodels
* Interpret p-values and statistical significance
* Draw data-driven conclusions from experimental results
* Build interactive dashboards for data exploration
* Implement a three-tier software architecture

## Project Workflow

### Data Collection

* Connected to a MongoDB database
* Retrieved synthetic experimental data
* Organized and prepared data for analysis

### ETL Process

* Built custom ETL classes
* Automated data extraction and transformation
* Structured workflows around the experimental hypothesis

### Statistical Analysis

* Created contingency tables
* Calculated odds ratios
* Conducted Chi-Square hypothesis tests
* Evaluated treatment effectiveness
* Interpreted statistical significance and p-values

### Software Architecture

Implemented a three-tier design pattern:

#### Database Layer

* Custom `MongoRepository` class
* Database connection and data retrieval

#### Business Logic Layer

* `GraphBuilder`
* `StatsBuilder`
* Statistical calculations and visualization preparation

#### Presentation Layer

* Interactive dashboard
* User controls with dropdowns and sliders
* Dynamic data visualizations

### Data Visualization

* Interactive bar charts
* Choropleth maps
* Experiment performance dashboards

## Technologies Used

* Python
* Pandas
* NumPy
* PyMongo
* MongoDB
* Statsmodels
* Plotly
* Dash

## Key Question

**Does sending an email significantly increase student enrollment at WorldQuant University?**

## Key Concepts

* A/B Testing
* Experimental Design
* Chi-Square Test
* Odds Ratio
* Hypothesis Testing
* Statistical Significance
* ETL Pipelines
* Object-Oriented Programming
* MongoDB
* Dashboard Development
* Three-Tier Architecture

## Repository Structure

* `notebooks/` – Analysis notebooks
* `dashboard/` – Interactive Dash application
* `data/` – Experimental datasets
* `images/` – Visualizations and screenshots
* `README.md` – Project documentation

## Reflection

This project demonstrated how statistical analysis can be integrated into a complete software solution. Beyond conducting a hypothesis test, I learned how to structure applications using software engineering principles, build reusable ETL pipelines, and create interactive tools that make statistical insights accessible to users. It highlighted the importance of combining analytical thinking with scalable application design.

## Author

Yogesh Kumar

Applied Data Science Lab — WorldQuant University
