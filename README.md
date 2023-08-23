# Text Analysis: Twitter News Sources
Here you can see a text analysis project using topic modeling and sentiment analysis that I completed looking at various news sources on twitter. 

# Files
The following files are available to download:
1. PDF: Final write up of project including all code, visuals and analysis. This is all you need to see the full project
2. Code: RStudio code file. This allows you to re-run the analysis on your own.
3. Data: Export of data scraped from Twitter used in analysis. This allows you to re-run the analysis on your own. 

# Project Topic
With so many news sources out there, it is common to get push notifications on your phone or see social
media posts about the same story from multiple different outlets.Based on this, I wanted to look into how
different news accounts were both similar and different by performing text analysis on their most recent
tweets.


News sources can be broken down into two main categories - Hard News and Soft News. Hard news includes
politics and business while soft news is focused on lifestyle and entertainment, such as sports and celebrity
coverage. For this analysis, I will be looking at tweets from both types of sources to see if they have any
overlap. The sources used are:
1. ENews
2. BuzzFeedNews
3. WSJ
4. NYTimes
5. Betches_Sup
6. CNN
7. TMZ


The main questions I will be looking at are:
1. How similar are twitter accounts of various news outlets?
2. For news outlets that report on similar topics, is the sentiment also the same?

# Conclusion

#### 1. How similar are twitter accounts of various news outlets?
While the models were able to distinguish between the hard and soft news sources, I haven’t yet been able to
model news stories as topics to the various accounts. It was interesting to see that betches sup was classified
as mostly hard news since most of their content is light-hearted reactions and interpretations to hard news
topics. The next steps here will be to continue to clean the data to see if it is possible to build topics that
represent the various news stories being discussed to see if certain sources talk more about one story than
another. To continue cleaning the data, I will want to remove more words until just key words about news
topics remain.

#### 2. For news outlets that report on similar topics, is the sentiment also the same?
Unfortunately, all of the accounts are majority negative, with the exception of enews. This was surprising
because often times celebrity news outlets have a reputation for being negative, but for each sentiment
analysis completed, enews appeared positive. This shows that enews may be sharing celebrity gossip in a
positive way and not only spreading dirty gossip. This was in contrast to buzzfeed and TMZ who both
tweeted about similar topics to enews, but had negative sentiments. Buzzfeed news was the most negative
which is interesting because I typically think of Buzzfeed as a somewhat lighthearted website and would have
expected the most negative to be TMZ. For the hard news accounts, it is not surprising that betches_sup
was the most positive out the group but it was surprising how different betches_sup’s average polarity score
was from the others.
