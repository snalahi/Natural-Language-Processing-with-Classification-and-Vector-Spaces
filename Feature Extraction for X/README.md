## Documentation for feature extraction for X
#### Build frequencies dictionary => 
`freqs` will be a dictionary of all unique words found in all the tweets in the text corpus with two classes such as positive frequencies and negative frequencies.

#### Initialize matrix X => 
input matrix X is initialized with size (m, 3) where m is the number of total tweets considered to be fed into the model and 3 for three different dimensions such as bias, sum of positive frequencies for each tweet, sum of negative frequencies for each tweet.

#### Process tweet =>
will process the tweet at the i-th position to be list of words or stems to be fed in the extraction function.

#### Extract Features =>
it takes the processed tweet as a list of words and the `freqs` which is a dictionary containing vocabulary and two possible classes with frequencies. Here the processed tweet is mapped to the frequencies and outputs a bias item of 1, sum of all the positive words frequencies and sum of all the negative words frequencies. Finally, X[i, :] = X[i-th row, all columns] is set equal to extracted features of dimension (1, 3).
