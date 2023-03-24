## **Optimization Functions: Mini-Batch Gradient Descent**


Dataset
This is a dataset of 11,228 Reuters news articles labeled with 46 topics.

It was originally generated through analysis and preprocessing of the classic Reuters-21578 dataset, but the preprocessing code is no longer packaged with Keras.

Each news article is encoded as a list of word indices (integers). For convenience, words are indexed by their overall frequency in the dataset, so for example, the integer "3" encodes the third most frequent word in the data. This allows for fast filtering operations such as "consider only the top 10,000 most common words, but remove the 20 most common words".