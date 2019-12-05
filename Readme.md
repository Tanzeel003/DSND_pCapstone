# Sparkify project - predicitng churns with Spark

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Dataset](#dataset)
4. [Files Description](#files)
5. [Result](#Result)
6. [Licensing, Authors, and Acknowledgements](#licensing)

This project uses PySpark to predict churn based on a 12GB dataset of a fictitious music service platform, "Sparkify". Check out my <a name = "https://medium.com/@haidertanzeel003/the-project-provided-by-udacity-is-about-analyzing-user-behavior-of-a-music-app-sparkify-45db5d51ea57">blog</a> post for more details!

## Installation <a name="installation"></a>

This project uses the following software and Python libraries:

Python
Spark
Pyspark
pandas
Matplotlib
Seaborn

You will also need to have software installed to run and execute a Jupyter Notebook.

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more. And for Spark, you can do this using AWS or IBM Cloud.

## Project Motivation<a name="motivation"></a>

This is udacity's capstone project, using spark to analyze why user churn from music app Sparkify. 
Churn is a common problem in any industry. It is believed that any business would have a higher life time value coming from Existing customers vs. New acquired customer bases.

Sparkify is a music app. The dataset provided to us contains two months of sparkify user behavior log. The log contains some basic information about the user as well as information about a single action. A user can contain many entries. In the data, a part of the user is churned, through the cancellation of the account behavior can be distinguished.

## Dataset<a name="dataset"></a>

Activity dataset from Udacity
The dataset logs user demographic information (e.g. user name, gender, location State) and activity (e.g. song listened, event type, device used) at individual timestamps.

A small subset (~120MB) of the full dataset was used for data analysis and modeling as I didn't have enough resources for AWS


## Files Description<a name="files"></a>

**Sparkify.ipynb** Main code file of the project, it demonstrates the process of using pyspark to explore the data and build the model.

## Result

According to the results of the model, it is time after registeration, then the average time spent on each song and then the frequency of Thumbs Down that has the greatest impact. Churn users have more Thumbs Down. Naturally, users will leave if they are not satisfied.


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Udacity for the project. You can't use this for you Udacity capstone project. Otherwise, feel free to use the code here as you would like! 
