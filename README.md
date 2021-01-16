# Udacity-Data-Science-Capstone-Project
PySpark programming with Data Science Capstone project - SPARKIFY

## Sparkify Project Overview:
Sparkify is a digital music service where users stream their favorite songs whenever they pleases, either using free tier that places advertisements in between the songs, or using the paid subscription model where they pay a monthly flat rate. User can upgrade, downgrade or cancel their service at any time they want.  This music streaming service Sparkify is more like Spotify, Pandora or Amazon music streaming services.

This project is the final Capstone project of the Udacity Data Scientist Nanodegree program. The objective of this project is to learn how to manipulate realistic datasets using  pySpark programming language. We will be converging our investigative analyses in figuring out why certain customers are leaving the steaming service. Once we distill out possible reasons with customer `churning/leaving`, we might be able to emulate and apply those findings in a bigger data environment.

So, our job is to perform churning related data analysis and doing feature engineering by mining the customers' data, then implementing an appropriate model to predict possible customer churning. The goal if we’re able to predict precisely, when and how possible customer churning might happen, we can identify customers and offer them relevant promotion and will be able to retain them as continued customer thereby maximizing revenues.

## Blog post:
Please check my blog post to get more details, here is the link.

## Key Steps for Project
Load the `mini_sparkify_event_data.json` datasets.

Creating Python Jupyter Notebook with a Spark session added.

Using PySpark and Python interchangeably for better graphical presentation. 

## Programming sequence for Supervised Binary Classification:
- Exploratory data analyses: Basic statistical data analyses.
- Detail missing value analyses correlated with 'userId' reasonings.
- Questioning data and presenting findings in a visualized format using pySQL.

## Detail page feature analyses in relation to churning behavioral trend:
- Comparative churning behavior analyses with multiple scatterplots and location based churning projections.
- Feature engineering: Redesigning new columns from existing features and streamlining them readying for data modeling.
- Vectorizing,  Scaling, Under-Sampling the datasets and readying them for data modeling.
- I choose logistic regression, linear svm, decision tree and random forest classifier to train for baseline model algorithms.
- Parametric tuning of the baseline model for better model performance.

#### Project submission link: [my project on Github](https://github.com/farhadkpx/Udacity-Data-Science-Capstone-Project-)

## Key File Descriptions:
1. mini_sparkify_event_data.json: Carefully fabricated music streaming data was provided by Udacity. This file is not available in the repository due to enormous size.
2. sparkify.ipynb:  PySpark  notebook I’ve created with all necessary steps to build multiple models that predicts churn from the Sparkify data.

## Running Jupyter notebooks:
PySpark works incredibly slow while running `Machine Learning model-algorithms` on desktop/Laptop processing environment. Unless you have clustered or cloud computing access, I would say be patient and let your machine do what it supposed to do.

## Result Summary:
Though the LinearSVC spent more training time, but it can get the highest f1 score 0.702. And the LogisticRegression has a medium training time and f1 score, maybe I can tuning it to get a higher score. So I'll choose LinearSVC and LogisticRegression to tuning, and the result is as follows:

## Dataset Scope:
We worked on a smaller dataset contains a subset (128MB) of the full dataset available (12GB). I doubt this smaller data subset is truly representative of the main set?

## Licensing…acknowledgement:
Since Udacity has provided us this dataset, they must get the credit as the true provider of Sparkify dataset. So I don't have any licensing entanglement to share with.
