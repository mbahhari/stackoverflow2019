
# Introduction
Every year Stackoverflow performs a survey for developers all around the world.  I will do some analysis for the 2019 survey, regarding most programming languages, the most desired languages and finally do some analysis on developers from Arabic countries and show which country participated and Total income for those countries

[Link to the article](https://medium.com/@mobahhari/scartch-the-surface-in-stackoverflow-users-survey-in-2019-9e0b00d24988
) </br>


## Libraries Used:
> Counter and defaultdict from collections library</br>
> pandas Library #To enigneer data</br>
> import matplotlib.pyplot as plt</br>

## CRISP-DM
* This analysis will performed on stack overflow developers survey in 2019. This survey holds a large amount of informations regarding the developers languages, working status, professional or hobiests, Incomes etc... . 
* The dataset contains a lot of nan values. Regarding the first two questions out of three focusing in two columns (LanguageWorkedWith, LanguageDesireNextYear].
</br> first I changed name of c language to CLanguage and Java to JLanguage as these two languages has similar name with first part of other languages, 
</br> split ecah language for each row to columns.
</br> Drop nan values in each row 
<br> create a dataset contains (Languages,Users) 

The second question required to count each language occured in both two columns row by row.
</br> 
For the last question, a sub dataset created from the main dataset filtered by country of the developrs [Arabic countries] 
[Saudi Arabia','Egypt','Bahrain','Jordan','Qatar','Syrian Arab Republic','Yemen','United Arab Emirates','Kuwait','Tunisia','Morocco','Algeria','Libyan Arab Jamahiriya','Oman','Lebanon','Iraq']]

* Evaluating 
### Question 1 : What are the most language used by the developers, and what are the most desired languages to be work with next year
Plotting the new two datasets (current_lang,desired_lang) and perform analysis in these two datasets.
### Question2 : What are the most languses are the developers work with and want to continue work with next year.
Plotting the dataset created from the dictionary match
`match dictionary is a result of counting each language occured in both rows`
### Question 3 : What are the most paid in Arabic countries. 
Plotting the dataset regading ConvertedComp ' Anaula income in USD'. 


  
