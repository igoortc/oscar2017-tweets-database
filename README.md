# Oscars 2017 - Tweets database

Database containing tweets published between Jan 24th-Feb 25th, 2017 related to the movies nominated to Best Picture on the 2017 Academy Awards.

The movies are: Arrival, Fences, Hacksaw Ridge, Hell or High Water, Hidden Figures, La La Land, Lion, Manchester by the Sea and Moonlight
The database is available in four different formats:

* complete db - by week - contains metadata: all of the collected tweets in their original format, separated by week, containing all the metadata (# likes, # RTs, link, etc) 

* complete db - by week - without metadata: only the tweets collected (without the metadata), separated by week

* complete db - processed: only the tweets collected (without the metadata), separated by movie, pre-processed using the [tool that I created](https://github.com/igoortc/tweets-preprocessor)

* labeled db: part of the original database (0,36%) manually labeled with the sentiment expressed in each tweet (positive, neutral or negative). The files are separated by sentiment and the tweets were randomly chosen between all of the tweets collected. These files can be used as a training set for supervised classification algorithms. 

I used the tool [GetOldTweets](https://github.com/Jefferson-Henrique/GetOldTweets-python) to collect the tweets, and the data collected was classified using different classifiers. 
The data was used to write the paper "Sentiment analysis of tweets related to the movies nominated for the 2017 Academy Awards".

You can [read it](https://igoortc.github.io/research) (in Portuguese) and understand how I used the database in my paper.

**If you use any part of this database, please cite the paper! :)**
