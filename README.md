This is a MapReduce framework based on Python threads to count the number of times a word
occurs in the document.\

It involves following four functions:
1. The main function that reads the input text document, splits it into individual words, calls the map_reduce function and displays output.\
2. The mapper function maps the words to a key-value pair where the key is the word and the value is 1.\
3. The shuffler function shuffles the intermediate key-value pairs so that all the pairs with the same key are sent to the same reducer.\
4. The reducer reduces the key-value pairs by summing up the values for each key.\
