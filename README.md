# hourly_newscluster_today
Hourly-updated news cluster data for "Today" section on THISISALLABOUT.

## Info
Contains clustering result data from March 18, 2018 to February 8, 2019.
There are some missing dates due to maintenance.

## Technical details
Automatically aggregates stories from major news publishers every hour. During this process, it filters out stop words. To analyze a large amount of news data, clustering unit first vectorizes all word tokens. Then, it automatically determine a reasonable and optimal size of clusters. Once the initial data processing is done, the "interpreter" unit creates a final result, ready to be published.

This content renders clustering results created automatically by our processing system. We verify that the result is completely untouched.

We aggregate and process stories from CNN, Fox News, The New York Times, The Hill, Washington Post, The Wall Street Journal, NPR, Chicago Tribune, USA Today, Politico, L.A. Times, NBC News, PBS NewsHour, The Washington Times, The New Yorker, CBS News, C-SPAN, ABC News, The Atlantic, AP, The New Republic, The Boston Globe, Business Insider, CNBC, Bloomberg, and Financial Times from the past 24 hours.


## Technologies
* nltk 
* scikit-learn (tfidfvectorizer/kmeans/pca) 
* pandas 
* scipy 
* numpy 
* whoosh 
* lda — available on the last clustering set generated on Feb 08, 2019.
* Mongodb/pymongo (database)

## Copyright
* Data file and clustering result: MIT License. Owned by THISISALLABOUT (Seungyun Todd Oh).

* News Articles/Images copyrights CNN, Fox News, The New York Times, The Hill, Washington Post, The Wall Street Journal, NPR, Chicago Tribune, USA Today, Politico, L.A. Times, NBC News, PBS NewsHour, The Washington Times, The New Yorker, CBS News, C-SPAN, ABC News, The Atlantic, AP, The New Republic, The Boston Globe, Business Insider, CNBC, Bloomberg, and Financial Times.

## Contact
* Director: brklynfivefive @ gmail .com