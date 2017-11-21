# KMeans_CLustering
I read 10000 tweets. After collecting the tweets, I've cleaned the tweets by removing mentions and URL's. I have created tokens from each 
tweet. Then, I have created a vocabulary with unique words from all the tweets. 

Suppose if have tokens of one tweet as ['you', 'know', 'i', 'm', 'driving', 'off', 'without', 'second', 'guessing']. I created a context 
by passing the word index and window size. Suppose, word is 'driving' and window = 2, then I find the left 2 elements and right 2 elements
for the word 'driving 'from the above list.

As I have created dictionary for all the contexts, I need to vectorize it using DictVectorizer package in python. After vectorizing the data,
I used K-means algorithm from SKLearn and used 20 clusters. I created Matplotlib plots for differnt k values like [5,10,20,50,100].

As k value increases the score decreases because each point will form a cluster.
