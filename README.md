# Billboard.Hot.100
Analysis of Billboard Hot 100 song chart weekly chart data from 1999-2019 and relation to Grammy Wins

Tableau Story with conclusions:
https://public.tableau.com/app/profile/alanah.meeks/viz/BillboardHot100andGrammyWins/BillboardHot100andGrammyWins


Original Kaggle Dataset:
https://www.kaggle.com/datasets/danield2255/data-on-songs-from-billboard-19992019 

Kaggle Dataset Context:
Some of this data was gathered to do a research project at California Polytechnic State University in San Luis Obispo, and it eventually turned into my senior project where I completed it. This data is great for lots of exploratory data analysis routes, text analysis, feature engineering, or machine learning. It turned out to be a great interesting set of projects for me and I hope it does the same for you!
Content

This entire data package includes data from the following sources:

    Billboard Hot 100
    Spotify (and their API)
    Genius
    Recording Academy Grammy Awards
    Recording Industry Association of America (RIAA)


Of the provided datasets, only the following CSV files were utilized:
  - BillboardHot100_1999-2019.csv
  - grammysongs_1999-2019.csv



Project Context:
The goal of this analysis was to determine what components of a songs rise and fall on the chart can be predicted, how those trends change across genres and years and how likely we are to be able to predict a songs success on the chart based on its trajectory. We then take that information and see how it relates to a song's likelihood of achieving a grammy win. 

Challenges:
This dataset had some significant challenges associated, primarily with the integritiy of how the data was harvested and its cleanliness from source to CSV file. There were numerous errors in how the data populated, creating quite a bit of data cleaning to make the information truly workable. From there, the relation from the Billboard Hot 100 data to the grammy CSV files was limited at best. Short of reworking every single record, best path forward was to match what songs were able to and analyzing the information that was available. 

In addition, reducing the genre categorization was a significant challenge. Songs were worked into larger buckets to as accurate of an extent as possible. 
