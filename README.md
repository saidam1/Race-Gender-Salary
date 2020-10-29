![image](https://user-images.githubusercontent.com/70491460/97521886-dbd4f700-1974-11eb-9dad-d97f84414632.png)



# Race-Gender-Salary

## Table of Content

* Overview
* Goals
* Motivation and Background
* Data
* Software and Packages 
* Technical Notebook

## Overview 
Is it possible for us to create a machine learning algorithm that will estimate someone's salary based on their race, gender, education, age, and some other underlying facts about the person?

You would not be surprised if someone were to tell you that men get paid higher than women in the work industry, or that Caucasians get paid higher than African Americans. It has just become a fact at this point. Are there exceptions to this? If not is there a way for us to predict what a person is making based on their age, education, gender and race? If so how accurate will it be?

## Goals

* Shine light on the pay discrimination that occurs in the workplace.
* Try to use predicting models to really understand the discrimination in pay when it comes to race and gender. 
* Using the number of people from our data which shows the of people in the different countries, however we are focused in just the US, will we be able to make a good prediction on someones income based on their race, gender and other information provided in the data like age, education, and family status.

## Motivation & Background

There was a big schock in the United States and the world when Donald Trump won the 2016 presidential election. It shed light onto the racisim and sexism that has been long instilled in a lot of Americans and it has been passed generations to generations and is still happening. Four long years later we are back again in the midst of the elections for the 2020 presidential election. Now more than ever we see the racism not just in America but around the world increasing at a rapid rate. Maybe it's not actually increasing, but people are not afraid to show how they truly feel when there is a president that is blatantly supporting White Supremacy and Male superiority.  

The past two reports that I had done ties with racism in America. This one will dive a little deeper to see the instutitionalized discrimination that occurs when it comes to salary bias to African Americans and Women in the United States. 

The wage gap between genders can be attributed to factors that are measurable, such as differences in seniority or experience, however these types of observable factors cannot explain most of the portion of the gap. It is this unexplainable portion that leads us to believe it is solely due to gender discrimination. At the same time there is a wage gap between races that led to persistent wage disparities between workers of color and Caucasians, which also has unexplainable factors that stem from bias and racism.

https://www.americanprogress.org/issues/women/news/2019/08/22/473775/racism-sexism-combine-shortchange-working-black-women/

## Data

The data that was used for this study was obtained from the adult income salary data from Kaggle (https://www.kaggle.com/mastmustu/income?select=train.csv).

This data was extracted from the 1994 US census database, contatining information like occupation, age, native country, race, capital gain, capital loss, education, work class and more. 

It contains both categorical and continuous features.

The categorical columns being:
   * workclass
   * education
   * marital status
   * occupation
   * relationship
   * race
   * gender
   * native country. 
  
While the continuous columns being: 
   * age
   * educationnum
   * capital gain
   * captial loss
   * hours/week.

There was a total of 43957 rows and 15 columns.


## Software Reuqirenments -Packages used

* pandas
* seaborn
* statistics
* matplotlib
* sklearn
  * model_selection
  * KNeighborsClassifier
  * LogisticRegression
  * DecisionTreeClassifier
  * RandomForestClassifier
  * GradientBoostingClassifier

## Technical Notebook
https://github.com/saidam1/Race-Gender-Salary/blob/main/Race%2C%20Gender%2C%20and%20Salary%20Technical%20Notebook%20(1).ipynb
