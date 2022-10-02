# DSAI-FinalProject-2022
This is a final project (homework) of the [NCKU](https://www.ncku.edu.tw/index.php?Lang=en) course which named [Competitions in **D**ata **S**ciences and **A**rtificial **I**ntelligence (資料科學與人工智慧競技)](http://class-qry.acad.ncku.edu.tw/syllabus/online_display.php?syear=0110&sem=2&co_no=P75J000&class_code=).
## FINAL PROJECT DESPRICTION
Select one of the following **kaggle competitions** to participate in. 
* JPX Tokyo Stock Exchange Prediction
  * https://www.kaggle.com/competitions/jpx-tokyo-stock-exchange-prediction/data
* Foursquare - Location Matching
  * https://www.kaggle.com/competitions/foursquare-location-matching
* Google Smartphone Decimeter Challenge 2022
  * https://www.kaggle.com/competitions/smartphone-decimeter-2022
* (Optional) U.S. Patent Phrase to Phrase Matching
  * https://www.kaggle.com/competitions/us-patent-phrase-to-phrase-matching/overview
* (Optional) Predict Future Sales
  * https://www.kaggle.com/competitions/competitive-data-science-predict-future-sales

And the results will be calculated by comparing the scores of the models with those of the students selected for the same competition in a fair ranking.
## CHOOSE COMPETITION: [Foursquare-Location Matching](https://www.kaggle.com/competitions/foursquare-location-matching)
### About this Competition
The data presented here comprises over one-and-a-half million place entries for hundreds of thousands of commercial Points-of-Interest (POIs) around the globe. 
**Your task is to determine which place entries describe the same point-of-interest.**
Though the data entries may represent or resemble entries for real places, they may also contain artificial information or additional noise.
### Training Data
* train.csv - The training set, comprising eleven attribute fields for over one million place entries, together with:
* id - A unique identifier for each entry.
point_of_interest - An identifier for the POI the entry represents. There may be one or many entries describing the same POI. Two entries "match" when they describe a common POI.
* pairs.csv - A pregenerated set of pairs of place entries from train.csv designed to improve detection of matches. You may wish to generate additional pairs to improve your model's ability to discriminate POIs.
match - Whether (True or False) the pair of entries describes a common POI.
## MY Strategy
* analysis and process input data
 * 
* Refer to the discussion forum for a [simple data cleaning code](https://www.kaggle.com/code/guoyonfan/simple-recall-method) and use [LightGBM](https://github.com/microsoft/LightGBM/tree/master/python-package) to further predict POI.
## Result
Although the class rankings are not publicly available, I got a score of **0.83880** on the [kaggle Leaderboard (search: **Kuihao Chang**)](https://www.kaggle.com/competitions/foursquare-location-matching/leaderboard)
It may not look like a high ranking now, but the competition was not over when the final project was submitted, and my code was ranked 139 at the time.
