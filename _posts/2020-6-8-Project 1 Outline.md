---
layout: post
title: Project 1 Outlines
---

This is my first project using data scientist methods to pull and analysis data.  

The project is about **JSON**, it can be accessed through this [link](https://luokan1227.github.io/Project1/).  

This project includes:  
## What is Json  
* Characters of JSON  
Listed some characters of JSON format.
* JSON data types (each includes Deinfiition, Syntax and Example)  
    + string  
    + number  
    + boolean  
    + object  
    + array  
    + null  
    + whitespace  
    + data types not available 
* Where does JSON been used  
The places we can JSON  
* Why we use JSON to store data  
Discussed the advantages of using JSON.  

## R Packages for reading JSON  
* Pull a data  
Introduced the steps of pulling **JSON** data from API.  
* Read in a JSON data  
Discussed three major methods of reading JSON data into R, compared their advantages and drawbacks.  

## NHL Records API Documentation  
Gave examples of pulling JSON data from API and analyzed by R.  

* Pull records  
Made a function to pull certain kinds of data from [NHL records ‘Franchise’ API](https://gitlab.com/dword4/nhlapi/-/blob/master/records-api.md).  
* Data analysis  
Pulled a example data and did some analyze with following methods.  
* Read in data  
Manipulate the raw data set.  
* Contingency tables view  
Analysis categorical variables by contingency tables and numeric summaries.  
* Bar plot view  
* Box plot view  
* Scatter plot view  

In this project, I practiced not only R coding, but also solving unexpected problems.  

The first challenge I met is how to work on my local R-studio and commit my code to GitHub. I found [a useful link](https://happygitwithr.com/rstudio-git-github.html) which introduced this process step by step. It's very detailed for new learner.  

Then I faced another problem, my R-studio couldn't handshake with the NHL API. I spend almost whole day on studing SSL/TSL handshake issues but still had no solution, until Dr. Post advised me to use VTL.  

After I finished almost all my code, I found I couldn't knit it on the VTL, it reported something denied. Then it took me a while to find out the Rmd file can only knit when it under the S:\ drive, but not under any folder.  

Every time I met those problems outside the coding, I felt frustrated, but when the problem been solved, I felt excited and encouraged. I think meet and solve problems are very important part of experience. Some problems worth do some research, some problems should use some smarter way to get rid of.  

Using GitHub to post a website link is very useful. I think I can organzie my lab protocols and share them through GitHub links.  It will be easy for both our team members and other cooperators to access.  
