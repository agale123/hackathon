# Twitter Sentiment Analysis

In this project, I scraped tweets during the Settle Reign v Chicago Red Stars game on 7/14/18. Keywords included the team names, player names, and the game hashtag. I collected the sentiment of each tweet and collected them into buckets. Below is the resulting graph that compared the sentiment during the game, to in-game events. During the game there were two serious injuries where sentiment was very negative, and then a huge jump in sentiment during the lone goal.

<img src="https://raw.githubusercontent.com/agale123/hackathon/master/sentiment.jpg" width="500px">

## Guide
To import tweets and write them to a file, run:
python3 twitter_import.py twitter_keys > twitter_out

To calculare the sentiment of each tweet in twitter_out and print out the sentiment values for tweets with non-zero sentiment, run:
python3 sentiment.py

To group tweet sentiments into buckets, run:
python3 twitter_bucket.py
