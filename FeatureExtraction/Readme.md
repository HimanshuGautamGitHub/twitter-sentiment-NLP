Given set of twitters line, and knowing in advance 
what are positive and negative words, we can predict others, Using Logistic regression and probability

Feature extraction is getting mathematical values for the text
Includes tokenizing string into words
idea:
convert text to vector class. use dictionary to count frequency of words

Problem: There can be huge number of words.So with huge dictionary, the regression will be slow

make vector more compact: sum all positive and sum of all negative words 
