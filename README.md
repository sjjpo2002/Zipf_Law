# Zipf's Law on Wikipedia Corpus
Word count is one the basic tasks in Natural Language Processing (NLP). According to Zipf's Law:
"For a given corpus of natural language utterance, the frequency of any word is inversely proportional to its rank in the frequency table. Thus the most frequent word will occur approximately twice as often as the second most frequent word, three times as often as the third most frequent word, etc."- Wikipedia
To verify the theaory we need to find the most popular words in a relatively large natural language corpus. How about using the whole Wikipedia articles as the corpus! It seems to be a good fit for this purpose. Using Apache Spark we find the top 20 popular words in Wikipedia.
