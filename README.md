![](https://forthebadge.com/images/badges/made-with-python.svg)

# Recommendations with IBM

## Table of Contents
- [Introduction](#Introduction)<br>
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)<br>
- [Rank Based Recommendations](#Rank)<br>
- [User-User Based Collaborative Filtering](#User-User)<br>
- [Content Based Recommendations (EXTRA - NOT REQUIRED)](#Content-Recs)<br>
- [Matrix Factorization](#Matrix-Fact)<br>
- [Files](#Files)<br>
- [Licensing and Acknowledgements](#Licensing)

## <a name="Introduction">Introduction</a>
For this project you I analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles I think they will like. Below you can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.

<img src="ibm.png" alt="Articles"/>

## <a name="Exploratory-Data-Analysis">Exploratory Data Analysis</a>

Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.

## <a name="Rank">Rank Based Recommendations</a>

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

## <a name="User-User">User-User Based Collaborative Filtering</a>

In order to **build** better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

## <a name="Content-Recs">Content Based Recommendations (EXTRA - NOT REQUIRED)</a>

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

## <a name="Matrix-Fact">Matrix Factorization</a>

Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.

## <a name="Files">Files</a>
<pre>
.
├── Recommendations_with_IBM.html----------# HTML EXPORT OF JUPYTER NOTEBOOK
├── Recommendations_with_IBM.ipynb---------# ANALYSIS NOTEBOOK
├── data
│   ├── articles_community.csv-------------# INFORMATION ABOUT ARTICLES
│   └── user-item-interactions.csv---------# USER-ARTICLE INTERACTIONS
├── project_tests.py-----------------------# UNIT TESTS FOR PROJECT
├── top_10.p-------------------------------# BINARY FILE TO CHECK MY SOLUTION
├── top_20.p-------------------------------# BINARY FILE TO CHECK MY SOLUTION
├── top_5.p--------------------------------# BINARY FILE TO CHECK MY SOLUTION
└── user_item_matrix.p---------------------# BINARY FILE TO CHECK MY SOLUTION
</pre>

## <a name="Licensing">Licensing and Acknowledgements</a>

[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)

This project is part of [Udacity](https://www.udacity.com/) Data Scientist Nanodegree. 



**Copyright (c) 2022 Juma Hamdan**