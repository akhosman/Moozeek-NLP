![](https://github.com/akhosman/Moozeek-NLP/blob/main/Photos/Moozeek%20Banner2.png)

### About Moozeek:
Moozeek is a new streaming app which lets you listen to tunes from major labels on the web or via the Moozeek app. Like it's competitors: Pandora and Spotify, Moozeek recommends similar artists to your playlist but also adds new and upcoming artists based off similarities and artist selection upon creating an account. 




### Problem Statement: 
Moozeek would like to add a 'relevant artists' section solely formulated from recent keyword searches in their app for a more accurate listening experience. To do so, I will scrape data from two artist's subreddits, of different genres, find the top keywords fans use the most, and use different modelling methods.

* Our focus subreddit group will be r/lanadelrey and r/metallica.
* Deep dive into common topics and those lacked of by ldr subreddit to bring in new users/listeners.
* Identify the classification model with higher accuracy/recall score to get the key differences that a Moozeek needs to improve attraction from the competitor's audience.
* Communicate out the improvement criterias to bring in better subscription rates to maximize profit from marketing expenses.





### Conclusion and Recommendation:
Conclusion & Recommendations In conclusion, the model we chosed to better classify the posts for r/lanadelrey and r/metallica is the linear regression model with tfid vectorizer due to its higher r2 score, recall and f-1 score as a whole.

Besides maximizing the funds and manpower to classify posts from two different subreddits based on their title and selftext, there are a number of other possible applications for this model.

By looking at the probabilities associated with each post, marketing teams can better appeal to the potential listeners when they are promoting to the LDR fans or Metallica fans. In fact, this can also be useful as words can be trending with time but withi this model we can accurately ride the trend with words that have high probability of being classified as artist names and song names.

The sentiment analysis we implemented can also determine the mood of the potential clients which either is a positive attraction or vice versa.

The recommendation we would propose at this point of time for the Moozeek is that we can focus on are as follows:

* When someone wants to listen to a certain genre, they do not want to be interupted with a sudden change of tone/tune. Classifying keywords should be a priority to categorize the correct artist to the correct genre. Also, makes a run for a great listening experience.
* Dig further into keyword predicitions for moods in regards to genre.


* Corrected interactive scatterplot link: http://localhost:8888/files/Downloads/Project_3_ldr_Metaln_Sentiment_Analysis.html?_xsrf=2%7C6e5c73ca%7C201cad0dfde995af6d8bc91fb8a64d37%7C1650650845


### Resources:
* nltk- https://stackoverflow.com/questions/41610543/corpora-stopwords-not-found-when-import-nltk-library
* spaCy- https://spacy.io/models#available-models
* matplotlib colors- https://matplotlib.org/3.5.0/gallery/color/named_colors.html
* wordcloud- https://www.datacamp.com/community/tutorials/wordcloud-python, https://github.com/amueller/word_cloud
* redditcleaner- https://github.com/LoLei/redditcleaner
* interactive scatterplot- https://stackoverflow.com/questions/64573529/display-html-in-python-notebook,
