# Research on car sales ads

Chukwuemeka Okoli <br>
Practicum by Yandex Project 2 <br>
April 16, 2021 

**Project description** <br>
You're an analyst at Crankshaft List. Hundreds of free advertisements for vehicles are published on your site every day.

You need to study data collected over the last few years and determine which factors influence the price of a vehicle. 

**Guiding Question** <br>
What factors influence price of a vehicle? 

## Table of contents

<div class="alert alert-block alert-info" style="margin-top: 20px">
    <ol>
        <li><a href="#objectives">Objectives</a></li>
        <li><a href="#data_source">Data Source</a></li>
        <li><a href="#technology_used">Technology Used</a></li>
        <li><a href="#structure_notebook">Structure of Notebook</a></li>
        <li><a href="#executive_summary">Executive Summary</a></li>
        <li><a href="#accomplishments">Accomplishments</a></li>
    </ol>
</div> 
<br>

<div id="objectives">
    <h2>Objectives</h2> 
</div>
The objective of this project is to:

- Determine which factors influence the price of a vehicle.
- Apply Exploratory Data Analysis to a real-life analytical case study.

<div id="data_source">
    <h2>Data Source</h2> 
</div>


**Description of the data**

The dataset contains the following fields:
- `price`
- `model_year`
- `model`
- `condition`
- `cylinders`
- `fuel` — gas, diesel, etc.
- `odometer` — the vehicle's mileage when the ad was published
- `transmission`
- `paint_color`
- `is_4wd` — whether the vehicle has 4-wheel drive (Boolean type)
- `date_posted` — the date the ad was published
- `days_listed` — from publication to removal

<div id="technology_used">
    <h2>Technology Used</h2> 
</div>

<ul>
    <li>Python</li>
    <li>Jupyter Notebook</li>
    <li>Pandas</li>
    <li>Numpy </li>
    <li>Matplotlib</li>
    <li>Seaborn</li>
    <li>Plotly</li>
</ul>

<div id="structure_notebook">
    <h2>Structure of Notebook</h2> 
</div>
<ol>
    <li>Open the data file and study the general information</li>
    <li>Data preprocessing</li>
        <ul>
            <li>Processing missing values</li>
            <li>Data type replacement</li>
        </ul>
    <li>Make calculations and add them to the table</li>
    <li>Carry out exploratory data analysis</li>
    <li>Overall Conclusion</li>
</ol>

<div id="executive_summary">
    <h2>Executive Summary</h2> 
</div>

**Introduction**

As a Data Scientists working for a car listing site, how do you determine the factors that influence vehicle price. The answer is to look at the data. In this [project](https://github.com/chuksoo/vehicle_price_analytics), a car listing company - Crankshaft List publishes free advertisements everyday, and is hoping you use your analytic knowledge to study data collected over the last few years to assist with business decision making. The goal is to determine which factors influence the price of a vehicle.

**Methods**

I first inspected the data using the [pandas](https://pandas.pydata.org/) library to obtain general information about the data. I processed the missing values, changed data type, and converted data to the right type. I made calculations and added new features to the data. I investigated the following parametesr - price, vehicle's age when the ad was placed, mileage, number of cylinders, and condition. I plotted histogram for each parameters created. Prior to analyzing the data, I determined the upper limits of outliers and removed them. I used the filtered data to plot new histograms and compared them with the earlier histogram. In analyzing the data, I studied how many days advertisements were displayed (days_listed). I plotted new histogram and calculated the statistics of the data in order to describe the typical lifetime of an ad. I then determine when ads were removed quickly, and when they were listed for an abnormally long time. 

I then analyze the number of ads and the average price for each type of vehicle. I studied whether the price depends on age, mileage, condition, transmission type, and color. I plotted box-and-whisker charts, and create scatterplots for the rest using the [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) libraries. Analysis the data was important in answering some of the business needs.

**Key Findings**



**Deployment and Application**


**Future Development**


<div id="accomplishments">
    <h2>Accomplishments</h2> 
</div>


