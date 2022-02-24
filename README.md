# Seattle Airbnb Analysis

As a part of Udacity Data Science Nanodegree, I created an analysis on Seattle Airbnb data.
Supposed that we want to improve our customers' satisfaction, we should understand about the condition of our business and the feedback of our customers.
To do this, there are many questions can be asked, but in this analysis I would like to focus on answering these questions :
1. How occupied were the Airbnb housings in Seattle?
2. Is there any significant differences of average reviews scores between neighbourhood groups?
3. How good or bad were the sentiments of the users to the housings?

After doing the analysis, we can infer that some of the housings were always fully occupied, while some others were never be occupied througout the year. We could also see the declining trend of occupancy throughout the year, except on some certain occasions. Besides, we could also see that there is mainly no significant difference of the average rating scores for each neighbourhood groups, except for University District, where it was significantly lower than others.
Reviewing the feedback from the customers, most of them gave positive feedback, and a significant amount of neutral feedback was given, due to automatic review feature of the application.The dominant keywords for both negative and positive feedbacks can be utilized as a basis for improvement target.
Additionally, s the listing data contains longitude and latitude data, we can visualize them on a map.

The libraries I used to support this analysis are including numpy, pandas,matplotlib, nltk, langdetect, and wordcloud.
This repository contains the Jupyter Notebook file, as well as the necessary data : calendar, listings, and reviews, which are located in seattle.zip file.
1. calendar.csv
This dataset shows the daily availability of each housing. 
2. listings.csv
This dataset shows the current profile of each listings.
3. reviews.csv
This dataset shows the reviews by users.

Some external references I used to improve my analysis are :
https://medium.com/@b.terryjack/nlp-pre-trained-sentiment-analysis-1eb52a9d742c
https://pypi.org/project/langdetect/
https://www.datacamp.com/community/tutorials/wordcloud-python
https://towardsdatascience.com/easy-steps-to-plot-geographic-data-on-a-map-python-11217859a2db



