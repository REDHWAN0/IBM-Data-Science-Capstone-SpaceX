# IBM-Data-Science-Capstone-Project-SpaceX

# Introduction

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/api/Images/landing_1.gif)

## Background
SpaceX, a leader in the space industry, strives to make space travel affordable for everyone. Its accomplishments include sending spacecraft to the international space station, launching a satellite constellation that provides internet access and sending manned missions to space. SpaceX can do this because the rocket launches are relatively inexpensive ($62 million per launch) due to its novel reuse of the first stage of its Falcon 9 rocket. Other providers, which are not able to reuse the first stage, cost upwards of $165 million each. By determining if the first stage will land, we can determine the price of the launch. To do this, we can use public data and machine learning models to predict whether SpaceX – or a competing company – can reuse the first stage.

# Summary
* SpaceX API and Wikipedia launch table data was collected.
* Data was cleaned in preparation for visualizations, queries and machine learning model creation.
* Exploratory data analysis (EDA) was done using visualization and SQL.
* Interactive visual analytics were created using Folium and Plotly Dash.
* Predictive analysis using classification models was done.

# Methodology

## Data Collection -
* Using SpaceX Rest API
* Using Web Scrapping from Wikipedia

## Data Wrangling
* **Convert outcomes** into 1 for a successful landing and 0 for an unsuccessful landing
* Filtering the data
* Dealing with missing values
* Using One Hot Encoding to prepare the data to a binary classification

## EDA with Visualization
* **Create charts** to analyze relationships and show comparisons

## EDA with SQL
* **Query the data** to understand more about the data

## Maps with Folium
* **Create maps** to visualize launch sites, view launch outcomes and see distance to proximities

## Dashboard with Plotly Dash
* **Create dashboard**
* Pie chart showing successful launches
* Scatter chart showing Payload Mass vs. Success Rate by Booster Version

## Predictive Analytics

# Results

### Exploratory Data Analysis:
* Launch success has improved over time
* KSC LC-39A has the highest success rate among landing sites
* Orbits ES-L1, GEO, HEO, and SSO have a 100% success rate

### Visualization / Analytics:
* Most launch sites are near the equator, and all are close to the coast

### Predictive Analytics
* All models performed similarly on the test set. The decision tree model slightly outperformed when looking at .best_score_

# Conclusion
* SpaceX does not have a perfect track record of Falcon 9 first stage landing outcomes.
* SpaceX’s Falcon 9 first stage landing outcomes have been trending towards greater success as more launches are made.
* The machine learning models can be used to predict future SpaceX Falcon 9 first stage landing outcomes.

