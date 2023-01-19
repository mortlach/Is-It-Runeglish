# Is It Runeglish?

## Methods to 'accurately' estimate if a text fragment in runes is valid english

### A sample rune-text is chunked (with or without extra word length data) and its probabilty of occuring in the corpus looked up. Using the number of chunks and the probabilties a score between 0 and 1 can be given, where 1 means high confidence of runeglish, and 0 is low confidence of runeglish. The methods can work work for samples of text from 2 to 30 runes long (and adapted for >30). Increasing the number of runes will give more reliable results. Currently, it is recommended to use at least 12, but fewer can be used at your discretion.

### These methods can be used with automated decrypting efforts to spot Runeglish as key, or Runeglish as plaintext. 

### Read and run runeglish_tests.py

### Due to github file size limits ngRB3LogProbA.csv and ngRB3LogProbA.csv are the same dataset split over multiple files. Files can be cropped if needed (i.e. remove entries with counts < X) 

### For more info. you know where to find me, or, wait for updates to be posted here (!)