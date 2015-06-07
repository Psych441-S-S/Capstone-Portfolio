#Codebook for rawdat.csv

The data in raw.csv represent data from participants who took the Survey off of Survey Monkey (https://www.surveymonkey.com/s/GXH5KGK). Students from Eastern Oregon University were offered extra credit in their Psychology courses for partaking in the experiment. These data
were compiled using the preprocessing.R R script and are suitable for data analysis.

It should be noted that the data contain some values that are impossible to obtain
when properly completing the experiment. There were two observations that we did not use due to an incomplete survey.

The data file includes 5 variables.

* **Condition**: A factor variable indicating the group participants were in by virtue of their
birth month. This variable determined whether participants were put into the control condition- with no peer influence, or the conformity condition-peer influence.
    1. January, March, May, July, September, and November
        * Participants who were born in these months and selected this questions were given the mathematical equation without any peer influence.
    2. February, April, June, August, October, and December
        * Participants who selected this answer were given the mathematical equation with peer influence, in the form of percentages, next to the answers to the question.
* **Response**: A factor variable identifying individual participants selected responses to the mathematical equation.
* **Sex**: A factor variable indicating the sex of the participants.
* **Age**: A factor variable indicating the age of the participants.
* **Education**: A factor variable indicating the highest level of education the participant  received. 