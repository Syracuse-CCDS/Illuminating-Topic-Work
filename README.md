# Topic-Work
Author: Wenzhe Yang, Shloak Gupta, Ania Korsunska, Jennifer Stromer-Galley

The scripts of  topic work, including the train and testing dataset, scripts of lexicon developing and tagging. 
The vailidataion data is in the file named "The Dataset", thel exicon version and its coding results 
are in the file named "Lexicon version and results" The lexicon tagging and development includes following:

## The tagging script 
This script is for tagging the data set with the developed lexiocn and the pre-trained language model.
We applied a pre-trained language model — spaCy2.2 English Language Model — to do the n-gram tokenization and matching. 

## Finding more language cues with Word2Vec embedding and Support Vector Models (SVM)
A file contains the processing scripts including:
1. SVM classification
2. one-hot encoding
3. Find Topic with Word2Vec (Generate TSV files and illustrated the word embedding on http://projector.tensorflow.org/)
4. develop covid lexicon 

## Optimize the lexicon 
1. find the missclassifing seed words
2. calculate the ratio of correct
3. Make new lexicon (Version1-Version4.7)
4. FB-extend-lexicon: extend the lexicon from facebook data
5. tw-extend-lexicon: extend the lexicon from twitter data
6. Lexicon.doc sets of seed words after editing by human annotator
7. Combine data set and one-hot-encoding: data pre-processing for SVM classification
8. 2020 FB ads lexicon test-the raw lexicon : test the raw lexicon on classifying 2020 facebook ads and see its performance

