# Wrangle and Analyze Twitter Data

In this project I took tweet data from the popular WeRateDogs twitter account. WeRateDogs
regularly posts images of dogs from all over and gives them a unique rating. Gathering the data for this project involved taking data from a few different sources. The bulk
of the data was provided, but was a bit messy. Before this data could be used in analysis and
visualization I had to clean it up a bit so that it all worked smoothly. Another source of data
involved using Twitter’s API to get even more information about the WeRateDog tweets.

## Contents

**act_report.pdf** communicates the insights and displays the visualization(s) produced from the wrangled data. This is framed as an external document, like a blog post or magazine article.

**image-predictions.csv** contains the tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network.

**tweet_json.txt** is where each tweet's JSON data is stored. The data was retrieved by querying Twitter's API using Python's *Tweepy* library.

**twitter_archive_enhanced.csv** is the provided main dataset.

**twitter_archive_master.csv** is the final clean DataFrame.

**wrangle_act.ipynb** is the Jupyter notebook where all the gathering, assessing, and cleaning tasks are carried out.

**wrangle_report.html** describes wrangling efforts. Framed as an internal document.

## License

MIT License
