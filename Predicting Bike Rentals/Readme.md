# Predicting Bike Rentals

## Table of Contents
* [Introduction](#Introduction)
* [Aim of the project](#Aim)
* [About the Dataset](#Dataset)
* [Process](#Process)
* [Findings](#Findings)

## Introduction

Many American cities have communal bike sharing stations where you can rent bicycles by the hour or day. Washington, D.C. is one of these cities. The District collects detailed data on the number of bicycles people rent by the hour and day.

Hadi Fanaee-T at the University of Porto compiled this data into a CSV file, which you'll be working with in this project. The file contains 17380 rows, with each row representing the number of bike rentals for a single hour of a single day. You can download the data from the University of California, Irvine's website



## Aim

In this project, we predict the total number of bikes people rented in a given hour. You'll predict the cnt column using all of the other columns, except for casual and registered. To accomplish this, you'll create a few different machine learning models and evaluate their performance.



## Dataset

Here are the descriptions for the relevant columns in the csv file:

instant - A unique sequential ID number for each row

dteday - The date of the rentals

season - The season in which the rentals occurred

yr - The year the rentals occurred

mnth - The month the rentals occurred

hr - The hour the rentals occurred

holiday - Whether or not the day was a holiday

weekday - The day of the week (as a number, 0 to 7)

workingday - Whether or not the day was a working day

weathersit - The weather (as a categorical variable)

temp - The temperature, on a 0-1 scale

atemp - The adjusted temperature

hum - The humidity, on a 0-1 scale

windspeed - The wind speed, on a 0-1 scale

casual - The number of casual riders (people who hadn't previously signed up with the bike sharing program)

registered - The number of registered riders (people who had already signed up)

cnt - The total number of bike rentals (casual + registered)



## Process

we will create a few different machine learning models and evaluate their performance.
Machine Learning models like linear regression, Decision Tree and Rainforest.

We used RMSE values to compare the accuracy of different models 



## Findings 

Compared to other alogorithms , Rain Forest Algorithm gave the best results in terms of rmse values