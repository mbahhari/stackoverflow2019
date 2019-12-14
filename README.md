
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
** first I changed name of c language to CLanguage and Java to JLanguage as these two languages has similar name with first part of other languages, 
** split ecah language for each row to columns.
** Drop nan values in each row 
  
