# Exploration of the factors that influenced students' math scores in PISA data
## by Erin Yuan


## Dataset

The original dataset contained 636 columns and 485490 rows. Since there were too many columns to fit in one investigation, I sliced out the ones I was most interested in and formed a new csv file called "new_data" which is in the same folder along with other files in my submission. The columns I selected are country, gender, mothers' job status, father's job status, whether to agree that listening in class is effective, how often do teachers show interest while teaching, wealth, time of computer use, students' mathematical interest, and finally the students' math scores. 

The dataset can be found here: https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip.
with feature documentation here: https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv.


## Summary of Findings

Through the univariate data exploration, we found that students' math scores presented a normal distribution, which had a mean value of 469 and a range from 55 to 903. The wealth distribution is a little bit left-tailed, with most of people having close to 0 coefficient wealth and more people having less than 0 compared with those having wealth coefficient higher than 0. The distribution of "time of computer use" is very right-tailed, which indicates that most students had limited time to access computers. However, the scores for "mathematical interest" contains noramlly distributed feature. The largest amount of students had a mathematical interest between 0 and 1. 

Additionally, the number of females and the number of males are very similar, which might give us fairer results. We are very surprised to see that none of the mothers or fathers are working full time for pay in our dataset. For students' mothers, none of them are not working but looking for a job. However, there are substential fathers who are in this status. However, the missing data here might lead to some incorrent conclusions. In our investigation, mothers/fathers' job status did not have much impact on math scores or any other factors. In addition, after some data wrangling, we found that students from USA are still not a lot in this survey. Therefore, we should consider the results more as a global finding that means more to the countries which had most responses, such as Mexico, Italy, Spain, Canada, etc. Another important finding is that teachers' interest in class had a direct relationship with students' mathematical interest. 

Teachers who showed interest in every lession resulted in highest students' interest towards math and teachers who hardly showed any interest resulted in lowest students' interest. Students who believe that listening in class is extremely helpful showed the highest mathematical interest and enjoyed least computer use. 

