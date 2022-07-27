# Airbnb Price Predictor 


## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [List of packages in detail] (#packages)

## General info
This project was created for a Machine Learning and Programming course. The aim was to create an algorithm, able to help renters to find the
optimal price depending on several criterium (we will detail them later). 
The problematic was very large, so we had to make some choice (about places, when..). For our part, we decided to have the largest point of view, that means the algorithm could be able to
perform for anywhere in the world. Nevertheless, this implies to lose in precision, because there is some heterogeneity among countries, but also between cities in a same country. 
At the begin, we decided to webscrap airbnb, but finally, we decided to take the "Airbnb-listings" Opendatasoft database (https://public.opendatasoft.com/explore/dataset/airbnb-listings/), because it offers a lot of data!

This project is divided into 4 parts (3 are notebooks, and Web-app is a .py script):
* Data processing 
* Regression task
* Classification task
* Web-application
	
## Technologies
Project is mainly created in Python with these packages:
* Pandas
* Streamlit
* Scikit-Learn


	
## Setup
To run this project:
* Data processing 
You need to download the database in Opendatasoft base, and name it "airbnb-listings.csv" while running "data-processing" notebook/
* Regression task
The notebook is named "ML_regression" and use "df_clean.csv".
* Classification task
The notebook is named "classification" and use "dataframe_classification.csv".
* Web-application
It uses all other csv files in data. 
To run it, you need to write the followings command lines:
```
$ cd ../scripts
$ streamlit run app.py

```


## Packages

All the packages used in notebooks are already included in last Python version. 
Only the app use exclusive packages that you should install before running the code! (maybe one or two are missing)
```
$ pip install streamlit
$ pip install folium
$ pip install streamlit_folium
$ pip install PIL
```

