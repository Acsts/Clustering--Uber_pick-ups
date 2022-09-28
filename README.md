# Unsupervised ML for clustering : Uber pickups in NYC

## Jedha Fullstack Certification
- email : antoine.costes@live.fr
- Video link : https://share.vidyard.com/watch/1nfKZvDSiWkrQgkVrrgE5s?

## Goal of the project

In order to **advise Uber drivers on where to be at which time**, the goal of this project is to **identify "hot-zones" from Uber pick-up requests data**, and display theses zones on a map.

We'll use 2 different clustering algorithms for this task (KMeans and DBSCAN) and compare their results.

## Datasets

The data provided for this project gathers Uber pick-uprequests in NYC from april to september 2014 and from january to june 2015, available [here](https://full-stack-bigdata-datasets.s3.eu-west-3.amazonaws.com/Machine+Learning+non+Supervis%C3%A9/Projects/uber-trip-data.zip). 
**This analysis focuses on September 2014 data.** 

## Getting started - Prerequisites

1. Clone this repository to create your project folder :
    ```sh
    git clone https://github.com/Acsts/Clustering--Uber_pick-ups.git
    ```

2. Installations : 

    All the source code is written in Python3. 
    The dependencies you need to run the code are listed in the 'requirements.txt' file, you can install them with pip by running 

    ```sh
    pip install -r requirements.txt
    ```

## Usage


### Visualizing analysis results without code

If you want to access the results of the analysis without running any line of code, all interactive visualizations are accessible in the 'figures' folder, in the form of .html files you can download and open with your web browser.  
You can also visualize them directly without downloading by copying their github link in https://htmlpreview.github.io/, developped by [niu-tech](https://github.com/niutech).  

These files corresponds to the outputs obtained from running the code in the notebook `Uber pickups clustering.ipynb`.





