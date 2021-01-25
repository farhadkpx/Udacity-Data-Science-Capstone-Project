# `Udacity-Data-Science-Capstone-Project`
PySpark programming with Data Science Capstone project - SPARKIFY

## `Sparkify Project Overview:`
Sparkify is an online digital music service where users stream their favorite songs whenever they pleases, either using free tier that places advertisements in between the songs, or using the paid subscription model with a monthly flat rate. User can upgrade, downgrade or cancel their service at any time they want.  This music streaming service Sparkify is more like Spotify, Pandora or Amazon music streaming services.

This is the final Capstone project of the Udacity Data Scientist Nanodegree program. The objective of this project is to learn how to manipulate realistic datasets using  pySpark programming language. Here we will be converging our programming analyses to figure out why certain customers are leaving the steaming service. Once we distill out the possible reasons with customer `churning/leaving`, we might be able to apply those findings in a bigger dataset environment.

So, our job is performing churning related data analysis, doing feature engineering by mining the customers' data and implementing appropriate ML models to investigate out possible reasons of customer churning. The goal is if we were able to predict precisely when and how possible customer churning might happen then we will identify those customers and offer them relevant promotions to keep them as continued customer thereby maximizing revenues.

## Blog post:
#### Please check my blog post on medium:[blog link](https://freda31k.medium.com/customer-attrition-analyses-on-sparkify-music-streaming-service-43441d275bf4)

## `Key File Descriptions:`
1. mini_sparkify_event_data.json: Carefully fabricated music streaming data was provided by Udacity. This file is not available in the repository due to enormous size.
2. sparkify.ipynb:  PySpark  notebook I’ve created with all necessary steps to build multiple models that predicts churn from the Sparkify data.

## `Key sequential steps of the Project:`
- Load the `mini_sparkify_event_data.json` datasets.
- Creating Python Jupyter Notebook with a Spark session added.
- Visual graphical analyses.
- Detail Feature engineering for model applications.
- Machine Learning algorithmic application both baseline and parametric.
- Detail findings analyses.

## `Programming sequence for Supervised Binary Classification:`
- Exploratory data analyses: Basic statistical data analyses.
- Detail missing value analyses correlated with 'userId' reasonings.
- Questioning data and presenting findings in a visualized format using pySQL.

## `Detail page feature analyses in relation to churning behavioral trend:`
- Comparative churning behavior analyses with multiple scatterplots and location based churning projections.
- Feature engineering: Redesigning new columns from existing features and streamlining them readying for data modeling.
- Vectorizing,  Scaling, Under-Sampling the datasets and readying them for data modeling.
- I choose logistic regression, linear svm, decision tree and random forest classifier to train for baseline model algorithms.
- Cross valued grid parameterization with these models.

#### My Project submission: [link on Github](https://github.com/farhadkpx/Udacity-Data-Science-Capstone-Project)

## `Running PySpark with Jupyter notebooks:`
PySpark works fine with Python Jupyter notebook except when I'm trying to run ML algorithms, it's painstakingly time riddled. Specially when I'm using parametric inputs, 
it could take hours for a single model to perform. So if you run my notebook then be patient with timing unless you have access to cloud computing services.

## `Result Summary:`
Logistic Regression model performed better comparative to Linear SVC and best among all the other models I tried. Time, iterations and grid input choice in all combinations it
provided the best performance.

## Dataset Scope:
We worked on a smaller dataset contains a subset (128MB) of the full dataset available (12GB). I hope this smaller data subset is truly representative of the main data set?

## Licensing and acknowledgement:
Since Udacity has provided us this dataset, they must get the credit as the true provider of Sparkify dataset. So I don't have any licensing entanglement to share with.
