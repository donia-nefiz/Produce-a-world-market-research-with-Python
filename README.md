# Produce-a-world-market-research-with-Python

My mission here for <i>La Poule qui chante</i> is to analyze the global chicken market to help them choose their direction for international development.

All data have been sourced from www.fao.org for the year 2017.

In the first part, we will start by determining the relevant indicators for our mission and prepare the data for the rest of the analysis.<br>
In the second part, we will :<br>
1/ Performs a Principal component analysis (PCA) in order to visualize and study the different components of our dataset,<br>
2/ Perform an Agglomerative Hierarchical Clustering (AHC) and then a K-means clustering,<br>
3/ Compare the two methods and give recommendations.<br>
 
## Data preprocessing summary :

 I. Explore and clean <a href="https://github.com/donia-nefiz/Produce-a-world-market-research-with-Python" target="_blank">world market research data</a><br>
     -- A. Worldwilde chicken consumption and sale (2017)<br>
     ---- 1. [chicken_consumption.csv](http://localhost:8888/edit/chicken_consum_2017.csv) : exploration and data cleaning<br>
     ---- 2. [chicken_availibility.csv](http://localhost:8888/edit/chicken_avail_2017.csv) : exploration and data cleaning<br>
     ---- 3. [chicken_availibility_per_habitant.csv](http://localhost:8888/edit/chicken_avail_per_hab_2017.csv) : exploration and data cleaning<br>
     ---- 4.  [chicken_production.csv](http://localhost:8888/edit/chicken_prod_2017.csv) : exploration and data cleaning<br>
     ---- 5.   [chicken_exportation.csv](http://localhost:8888/edit/chicken_export_2017.csv) : exploration and data cleaning<br>
     ---- 6.   [chicken_importation.csv](http://localhost:8888/edit/chicken_import_2017.csv) : exploration and data cleaning<br>
     ---- 7. Merge dataframes, explore and clean<br>
     -- Conclusion (part I/a)<br>
     -- B. Global macroeconomic and political data (2017)<br>
     ---- 1. [data_population.csv](http://localhost:8888/edit/data_population_2017.csv) : exploration and data cleaning<br>
     ---- 2. [data_political_stability.csv](http://localhost:8888/edit/data_political_stability_2017.csv) : exploration and data cleaning<br>
     ---- 3. [data_gdp_per_hab.csv](http://localhost:8888/edit/data_PIB_hab_2017.csv) : exploration and data cleaning<br>
     ---- 4.  [data_inflation.csv](http://localhost:8888/edit/data_inflation_food_month_2017.csv) : exploration and data cleaning<br>
     ---- 5. Final merge, explore and clean<br>
     -- Conclusion (part I/b)<br>
  Conclusion<br>
  
## Analysis summary :

  II. World market research data, analysis</a><br>
     -- A. Pre-processing<br>
     ---- 1. Anomaly detection<br>
     ---- 2. Data standardization<br>
     -- B. Principal component analysis (PCA)<br>
     ---- 1. Explained Variance Ratio and Scree plot<br>
     ---- 2. Correlation circles and projections of points<br>
     -- C. Clustering<br>
     ---- 1. Hierarchical Ascending Classification (HAC)<br>
     ---- 2. K-means clustering<br>
     ---- 3. Comparison of the two methods<br>
     ---- 4. The best countries selected for internationalization<br>
     ---- 5. Final recommendations<br> 
  
  
