<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>
<h3 align="center"><a href='https://www.udacity.com/course/data-scientist-nanodegree--nd025'>Udacity Data Scientist Nanodegree Program</a></h3>
<h4 align="center">Project I: Write a Data Science Blog Post</h4>

## Table of Contents
- [Installation](#installation)
- [Project Motivation](#motivation)
- [File Descriptions](#files)
- [Results](#results)
- [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
You need to be able to work in a Jupyter Notebook on your computer. The following packages (libraries) need to be installed. You can install these packages via conda or pip.

- Numpy
- Pandas
- Matplotlib
- Seaborn
- jupyterthemes
- gmplot (Google Map API from Google Cloud Platform)
 

## Project Motivation <a name="motivation"></a>

### AirBnB Boston Open Data Analysis
By analyzing AirBnB Boston Open Data, We can provide valuable informations to hosts and customer.

### 1. How do seasonal costs change?
Provide seasonal costs to customer. It can be used as a reference when planning a trip

### 2. Which features are most related to homestay cost?
Correlation analysis allows hosts to see which factors have a significant impact on price. As a result of the analysis, the factors that have the greatest influence on price were in the order of number of accommodates, number of bedrooms, number of beds, number of bathrooms, and number of guests included. So, when the host decides the price, it's easier to find the right price through these five factors than other factors.

### 3. What is different between superhost and regular host?
AirBnB Superhost have more benefits than regular host. If we know what is different between superhost and regular host, It is much easier to become superhost. By the analysis, Big differences between superhost and regular host in seattle are location and number of reviews. Unexpectedly, average review scores are very similar.

<hr>

## File Descriptions
Dataset files from https://www.kaggle.com/datasets/airbnb/boston

- README.md: To introduce and explain the project.
- Boston_Airbnb_DataSets:
  -calendar.csv: Calendar, including listing id and the price and availability for that day
  -listings.csv: Listings, including full descriptions and average review score
  -reviews.csv: Reviews, including unique id for each reviewer and detailed comments
- Project_Boston_Airbnb.ipynb: IPython Notebook for data preparation, modeling, evaluation

## Results <a name="results"></a>
The main findings of the code can be found at the post available [here](https://medium.com/@farhadabbasiamiri/airbnb-boston-open-data-analysis-692f6d63e5f2)

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Must give credit to Airbnb for the data. You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/datasets/airbnb/boston).
