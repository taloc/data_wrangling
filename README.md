# Data wrangling
Gathered and cleaned and visualized data from JSON files, csv and tsv from a twitter account


The project objective is 2 fold:

a) Gather, assess and clean a set of 3 datasets

b) Generate 3 insights and 1 visualization

3 datasets were used:
twitter-archive-enhanced.csv (provided)
image-predictions.tsv (downloaded programmatically)
tweet_json.txt (created by using tweepy).

A series of libraries (numpy, pandas, matplotlib, seaborn) and python methods were used to achieve the 2 objectives, the code can be found in file
wrangle_act.ipynb

Project output files:
twitter_archive_master.csv (a cleaned file), there's also a sqlite database created called tweetanalysis.db
wrangle_report.pdf (describes wrangling efforts, internal use audience)
act_report.pdf (communicates the insights and displays the visualization, audience at large).
