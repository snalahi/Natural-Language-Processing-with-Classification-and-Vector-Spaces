# Natural-Language-Processing-with-Classification-and-Vector-Spaces
Sentiment Analysis is done here using logistic regression and naive Bayes classifiers.

Locality sensitive hashing is a method that helps to perform efficient search.

Vocabulary - Collection of unique words appeared in a corpus.

Corpus - A collection of written texts, especially the entire works of a particular author or a body of writing on a particular subject. In linguistics and NLP, corpus (literally Latin for body) refers to a collection of texts. Such collections may be formed of a single language of texts, or can span multiple languages -- there are numerous reasons for which multilingual corpora (the plural of corpus) may be useful.

In word frequency analysis in a corpus, there will be a dictionary mapping where each word along with its class (positive(1)/negative(2)) will be mapped to its frequency (number of appearance).

Instead of learning V dimensions of features, we can just learn 3 dimensions of features and that is in the form of [The first feature would be a bias unit equal to 1, The second is the sum of the positive frequencies for every unique word on tweet m, The third is the sum of negative frequencies for every unique word on the tweet]

Stop words - Words that don't add significant meaning to the tweet/sentence/corpus. Stop words should be eliminated.

Stemming - Stemming is basically removing the suffix from a word and reduce it to its root word. For example: “Flying” is a word and its suffix is “ing”, if we remove “ing” from “Flying” then we will get base word or root word which is “Fly”. We uses these suffix to create a new word from original stem word. Another definition, Stemming in NLP is simply transforming any word to its base stem, which you could define as the set of characters that are used to construct the word and its derivatives. Example: sitting -> sitt -> sit.

Things to be done in Text Preprocessing =>
1. Eliminate handles(@) and URLs
2. Tokenize the string into words. 
3. Remove stop words like "and, is, a, on, etc." and punctuations.
4. Stemming- or convert every word to its stem. Like dancer, dancing, danced, becomes 'danc'. You can use porter stemmer to take care of this. Porter's Stemmer Algorithm: https://www.geeksforgeeks.org/introduction-to-stemming/ 
5. Convert all your words to lower case. 

For example the following tweet "@YMourri and @AndrewYNg are tuning a GREAT AI model at https://deeplearning.ai!!!" after preprocessing becomes [tun,great,ai,model]. 

matplotlib.pyplot is a collection of functions that make matplotlib work like MATLAB.

"autopct" in pyplot pie chart enables you to display the percent value using Python string formatting. autopct='%.1f%%' prints all the numbers before decimal point, then the decimal point, then one floating number and finally prints a percentage (%) by inserting two modulo signs after the formatter.

ASCII color codes at the beginning of the print statement can be used to change the color, as an example '\033[91m' for RED and '\033[94m' for BLUE and '\033[92m' for GREEN.

Tokenization is a way of separating a piece of text into smaller units called tokens. Here, tokens can be either words, characters, or subwords. Hence, tokenization can be broadly classified into 3 types – word, character, and subword (n-gram characters) tokenization. For example, consider the sentence: “Never give up”. The most common way of forming tokens is based on space. Assuming space as a delimiter, the tokenization of the sentence results in 3 tokens – Never-give-up. As each token is a word, it becomes an example of Word tokenization. Similarly, tokens can be either characters or subwords. For example, let us consider “smarter”:
1. Character tokens: s-m-a-r-t-e-r
2. Subword tokens: smart-er

Download anything from NLTK by the method nltk.download('')

import re => for RegEx (Regular Expression) in python. A Regular Expression (RegEx) is a sequence of characters that defines a search pattern. For example, ^a...s$ => The mentioned code defines a RegEx pattern. The pattern is: any five letter string starting with a and ending with s.

Number of columns = Number of dimensions in a Matrix




















