---
layout: post
title: Project 2 Outlines
---

This project is creating models to predict `shares` variable from [Online News Popularity Data Set](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity) by weekdays (Monday, Tuesday, ...).  

The analysis results and code of Rmd template and automation [is available here](https://luokan1227.github.io/Project2/).  

To do this proect, I firstly generate a weekday-parametered Rmd file includes following analysis:  
* Introduction section  
    + Data background  
    Read in the data and give brief describe on the data set.  
    + Purpose of analysis  
    The goal of this project.
    + Methods to use  
    Roughly introduced the two modeling methods will use in this project.
* Data  
Do the data sampling and split data into training and testing, briefly describle the data and variables that are important for the fits. Also set seed for reproducible   
* Summarizations  
Do some basic summary statistics on the training data, use log to normalize `shares` variable.  
* Modeling  
    + Random Forests  
    Use `train()` function to do RF fit, then do prediction on test data set.  
    + Linear regression model  
    Created 3 linear regression fits, compare those fits, and choose one for testing.  
    + Compare model  
    Compare the missaccuracy rates of RF model and linear regression model.  

Then using automation to cycle through the weekday variables, generate seven analysis on Monday, Tuesday, Wednesday, ..., respectively.  

The "machine learning" area was a kind of mystery for me. After these weeks of learning and practicing, I got some basic ideas and skill in this area, it's exciting and I really like it.  

My work is realted with antibody response in diseases or vaccines. The typicall work path is: we isolated tons of antibodies, obtain their sequence and genetic information, do 
experiments to findout which of them have neutralizing ability. The experiments take time and expensive, we typically don't have enough funding to screen all of them. Traditional way 
is select some antibodies contains neutralizing antibody characteristics by observation. I think we can use our known antibody database to train a model, to predict neutralizing or not 
neutralizing for our new antibodies. It may increase our chance of obtaining neutralizing antibody.  

After the project-1's practice on accessing GitHub by R-studio, this time I'm more focus on coding. I didn't felt there was any very difficult part. I took a little more time on 
automation, I first tried to put the automation code in Rmd file, but not work. I watched the course video multiple times to recognize those code should be ran in console directly. 
Practice on automation is also my big take-aways from this project.  

