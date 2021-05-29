## Documentation for feature extraction for X
Build frequencies dictionary => `freqs` will be a dictionary of all unique words found in all the tweets in the text corpus with two classes such as positive
frequencies and negative frequencies
Initialize matrix X => input matrix X is initialized with size (m, 3) where m is the number of total tweets available in the corpus and 3 for bias, sum of
positive frequencies for each tweet, sum of negative frequencies for each tweet
