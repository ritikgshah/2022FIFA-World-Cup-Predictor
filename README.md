# 2022FIFA-World-Cup-Predictor

2022 FIFA WC predictor.ipynb is a jupyter file containing all the python code used to generate the predictions. The elimination style tournament bracket created has visualization issues on github, but when this file and all supporting files are downloaded and run on your local machine, these issues will go away and the bracket will look much cleaner. The knockoutstage bracket is supposed to look like this:

<img width="1331" alt="Screen Shot 2022-05-09 at 9 17 43 PM" src="https://user-images.githubusercontent.com/51481040/174838688-ba20b876-11ab-43bd-b4fd-b758d2337935.png">

Sometimes when the program is run it will show that Iran will go to the knockout stages, while othertimes it will show that USA will go through since they are both predicted to score the same number of points in the same group. I do not have a tie breaker system in place, but this should not matter as either way Netherlands is predicted to defeat Iran or USA whoever the program says will go through to the knockouts.

Web Scraping_no run.ipynb is a jupyter file that has code for webscraping data that was used to pull different rankings from the web to be used in my predictions. 

fifa-world-cup-2022-fixtures.csv has the fixture data for the 2022 world cup as set by FIFA.

new_rankings.csv has the latest FIFA men's world rankings that will be used to make predictions for the world cup.

results.csv has the results of all international matches played and this data was taken from Kaggle.

2022 FIFA world cup predictor paper.pdf has a deatiled write up of my thought prcoess as I approached this question. There is an introduction, methods, discussion, results, and conclusion section which is written to explain the models I use, why I use them, and show what I found by using these models.

Note: This project was coded on Google colab, hence you might see some code for that process. The folder can be accessed on this link if you wish to run the project yourself: https://drive.google.com/drive/folders/1Adz_s3R4syPqRTGO-naV7bJ6Yipqlnwq?usp=sharing
