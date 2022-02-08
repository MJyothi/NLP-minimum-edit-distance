# Experiment with Minimum Edit Distance algorithm

Levenshtein distance is used to find the similarity between misspelled words of Birbeck spelling error corpus and words from Wordnet dictionary. The aim is to find top k words with minimum edit distance for each misspelled word, and check if the correct spelling of this word exists in the top k. We then find the average of success at k, for k = {1, 5, 10}, which measures if the correct spelling exists in the top-k retrieved by the algorithm.   

