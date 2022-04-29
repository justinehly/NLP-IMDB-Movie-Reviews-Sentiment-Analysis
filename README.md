# NLP-IMDB Movie Reviews Sentiment Analysis
 
In Python, load one of the sentiment vocabularies referenced in the textbook, and run the sentiment analyzer as explained in the corresponding reference. Add words to the sentiment vocabulary, if you think you need to, to better fit your particular text collection.

For each of the clusters you created in homework 7, compute the average, median, high, and low sentiment scores for each cluster.


Explain whether you think this reveals anything interesting about the clusters.
Comment: Interesting, there is clear separation between the clusters by each number from low to median. Clusters 3 and 4 both have the same high value and similar other values telling me that based on using 51 top words to cluster, there may only be 4 realistic clusters based on this analysis.

Final Comments:
I found that most of the reviews I pulled from the IMDB website have a more positive slant, and that is more than likely because I just selected the top 5 reviews of each film. A better approach is to randomly select reviews from each movie, but that requires more complex web scraping skills or perhaps I just grab all the reviews and once I have them captured, then randomly grab using a bag of reviews approach.
Keeping in mind that I mainly took the top 5 reviews of each movie or imdb comedy listing, a few neutral and negative reviews did come in, more than likely because the movie has only a few reviews and how imdb is ranking the reviews.