# Capstone Project - User churn on Sparkify


### Table of Contents

1. [Introduction](#introduction)
2. [What's included](#included)
3. [File Descriptions](#files_desc)
4. [Installation](#installation)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## Introduction <a name="introduction"></a>

Given that I were Data Scientist working for an online music streaming company called "Sparkify". Users' subscriptions on Sparkify are either Free-tier or Subscription. Both of types of users can cancel the subscription anytime. Cancelling subscription is called 'churn'. The project aims at building a model with Logistics Regression algorithm, trying to predict which users are likely to churn based on their behaviour on Sparkify.

For the detail documentation, please refer to a blog post on Medium:
<a href='https://medium.com/@kitsamy2k/create-a-model-to-predict-churn-users-8ed233147b14'>Blog post</a>

## What's included <a name="included"></a>

```text
(project folder)/
├── mini_sparkify_event_data.zip
├── Sparkify.html
├── Sparkify.ipynb
```


## File Descriptions <a name="files_desc"></a>

1. mini_sparkify_event_data.zip
    - Dataset containing users' behaviours on Sparkify. Since the file is zipped, the python program will automatically unzip it before reading.
2. Sparkify.html
    - The Jupyter Notebook file in HTML format.
3. Sparkify.ipynb
    - The Jupyter Notebook file containing source-code of data science process of predicting churn of users.

## Installation <a name="installation"></a>

The code should run with no issues using Python versions 3.6.3 with Spark '2.4.3'.

Python libraries used in the project:
1. pandas
2. numpy
3. pyspark
4. json
5. datetime
6. matplotlib
7. sys
8. zipfile 


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Code released under the MIT License. Must give credit to Udacity for the data.
