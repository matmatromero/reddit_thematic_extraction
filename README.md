# Condoms, FBI, and Jeffrey Epstein: Thematic Extraction of /AskReddit Comments in Reddit in 2019

Reddit's /AskReddit is the most popular and most commented subreddit on the website. Plenty of personalities are interacting in the subreddit, thus plenty of themes could be from the corpus of comments. In classifying and identifying themes in the /AskReddit subreddit, we can determine how people behave based on how comment on posts. To analyze the data and get themes from it, the Reddit comments in the Jojie database was mined and everything pertaining to AskReddit comments in 2019 were saved in an SQL database. Afterwards, the comments were tokenized via TFIDF Vectorizer and saved to dataframe for further analysis. Then, using the Non-Negative Matrix Factorization, dimensions were reduced for easier analysis. The comments were clustered via K-Means Clustering. The clustering method yielded for 4 optimal clusters which could be attributed to the following themes:

1. General Questions About Daily Life
2. Questions about Sex and Pleasure
3. Conspiracy Questions Specifically About the US Government and Jeffrey Epstein
4. Bot-Related Comments or Statements

For the year 2019, it is therefore believed that the comments and questions on the /AskReddit subreddit cluster into one of these four themes.


