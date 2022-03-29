# H-M-Personalized-Fashion-Recommendations

**Kaggle competition: H&amp;M Personalized Fashion Recommendations.**

[Kaggle H&M](https://www.kaggle.com/c/h-and-m-personalized-fashion-recommendations)

A group educational final project as a part of Recommender Systems course.

## Authors

**Skoltech Data Science MSc students:** Evgeniy Garsiya, Lina Bashaeva, Evgeniy Frolov, Julia Orlova

## Abstract

The main goal of this project was to participate in H&M Personalized Fashion Recommendations competition, where participants competed to create a recommendation system that provides product recommendations based on previous purchases. Unfortunately, we have not got into the top-25, but still showed quite good results, having tried many different models and ways of processing data.

## Description
In this competition, H&M Group suggests all participants to develop product recommendations based on data from previous transactions, as well as from customer and product meta data. There were no preconceptions about what information is useful, this was also our goal. The available meta data spanned from simple data, such as garment type and customer age, to text data from product descriptions, to image data from garment images. More specifically, we were required to predict what articles each customer would purchase in the 7-day period immediately after the training time period. Customers who did not make any purchase during that time were excluded from the scoring.

**Our tasks were the following:**
* Analysis of available data for prediction and subsequent preprocessing based on our assumptions and patterns that we considered significant.

* Implementation of simple basic models to get the first trial results and general overview.

* Application of more advanced models, both from scratch based on the knowledge and skills that we have acquired during the course, and taken from side resources and adapted to our specific goals.

* Submission the results and analyzing the scores for further attempts.

## Data review. 

For this challenge we were provided the purchase history of customers across time, along with supporting metadata.

**The available data was:**
* User information file (.csv) containing user id, age, postal code and some other columns.
* Product information file (.csv) containing article id, product and group code, color group, graphical appearance, section name, and text description.
* Product images (.jpg) of 1166 x 1750 pixels.
* Transaction file (.csv) - the training data, consisting of the purchases each customer for each date, as well as additional information such as price and sales channel. Duplicate rows correspond to multiple purchases of the same item.

Transaction file data example:

![Иллюстрация к проекту]()
