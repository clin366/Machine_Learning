In this program, we'll use EM algorithm for text clustering. It could be considered as one of the nature language processing technique.
The task is to group a set of text documents based on their topics. The following concepts will be use in this task.

1. Bag of Words
  The simplest model for text documents is to understand them as a collection of words. 
  What we do is counting how often each word appears in each document and store the word counts into a matrix, where each row of
  the matrix represents one document. Each column of matrix represent a specific word from the document dictionary. Suppose we 
  represent the set of Nd documents using a matrix of word counts.
