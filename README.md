# olympics_body_composition_EDA

##### Table of Contents  
[Project Motivation](#project-Motivation)  
[File Description](#file-description)  
[Results](#results)  
[Libraries and Dependencies](#libraries-and-Dependencies)  
[Licensing, Authors, and Acknowledgements](#licensing-authors-and-acknowledgements)  
 
## Project Motivation
For this project, I was interested in investigating body composition changes of Olympic
athletes over time. For this purpose, I analyzed a data set of 120 years of olympic
athletes. Mainly, I was interested in the following questions:

1. How did athletes’ physique change over time in team sports?
2. Do you even lift? Did athletes become stronger over time?
3. Can we say something about medalists?

My analysis focuses on the sports of basketball, volleyball, handball and ice hockey.

## Results
My findings are presented in a blogpost on [Medium](https://medium.com/@lars.palzer/when-bigger-is-really-better-1628c128407a).
For a quick summary, here are the main findings:
1. *Height matters!* The average athlete in basketball, volleyball, handball and ice hockey has become significantly taller over time. 
Interestingly, this development has somewhat saturated since the late 90s in basketball, handball and ice hockey.
2. *Strength matters!* In team sports with direct contact between components, the average body mass index has increased significantly. By this measure, ice hockey players are the most muscular, followed by handball and basketball players. For volleyball players, there have not been significant changes.
3. *Physical dominance matters!* We looked at how gold medalists compared to the average athlete in a given year and found that in all sports, the gold medalists tend to be taller and/or more muscular than the average. This observation is particularly strong in basketball.

## File Description
The analysis is contained in a single notebook olympics.ipynb. The data set is also provided in /data but is taken from Kaggle (see below).

## Libraries and Dependencies
The notebook uses the following Python libraries:
* [numpy](https://numpy.org)
* [pandas](https://pandas.pydata.org)
* [matplotlib](https://matplotlib.org)
* [seaborn](https://seaborn.pydata.org)

## Licensing, Authors, and Acknowledgements
The analysis is based on the "120 years of Olympic history: athletes and results" data set taken from [Kaggle](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results).
Feel free to use my notebook as you wish!