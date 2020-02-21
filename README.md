# Spark-Map-Reduce-Sentence-Embeddings
This project is based on the Humor Analysis project where we calculated sentence embeddings sequentially. Looking online through Spark NLP tools, I found no black-box way to get sentence embeddings in Spark, so I decided to use Map Reduce to distribute this work (since sequentially this can take a lot of time as data scales up).

The pre-trained word embeddings are from a file called glove.6B.50d.txt found here: https://nlp.stanford.edu/projects/glove/
