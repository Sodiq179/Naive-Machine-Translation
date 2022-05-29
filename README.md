# Naive-Machine-Translation
Implementation of a mini machine translation system that translates English to French.
## Data
The full dataset for English embeddings is about 3.64 gigabytes, and the French embeddings are about 629 megabytes. A subset of the embeddings for the words used in this project was extracted.
### Taking a Look at the data
- en_embeddings_subset: the key is an English word, and the vaule is a 300 dimensional array, which is the embedding for that word.
  - 'the': array([ 0.08007812,  0.10498047,  0.04980469,  0.0534668 , -0.06738281, ....
- fr_embeddings_subset: the key is a French word, and the vaule is a 300 dimensional array, which is the embedding for that word.
  - 'la': array([-6.18250e-03, -9.43867e-04, -8.82648e-03,  3.24623e-02,...
### Other Data
- en_fr_train is a dictionary where the key is the English word and the value is the French translation of that English word.
- en_fr_test is similar to en_fr_train, but is a test set. We won't look at it until we get to testing.

