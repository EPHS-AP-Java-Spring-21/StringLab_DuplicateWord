# StringLab_DuplicateWord

Given an Array of common words, copy all of the words to an arraylist, remove all the duplicate words and return the number of words that your method removed.

Think about how you might alpabatize these words. You can create another Array, Arraylist, but you have to write a method to do the task of getting the words in the correct order. Describe your strategy, in the comments of your code.

		String[] commonWords = {"the","of","and","a","to","in","is","you","that","it","he","was","for","on","are","as","that","it","he","was","for","with","his","they","I","at","be","this","have","from","that","it","he","was","for","or","one","had","by","word","but","not","do","how","their","what","all","were","we","when","your","can","said","that","it","he","was","for","there","use","an","each","which","she","do","how","their","if","will","up","other","about","out","many","then","them","these","so","some","her","would","make","like","him","into","time","has","look","two","more","write","go","see","number","no","way","could","people","my","than","first","not","what","all","were","we","water","been","call","who","oil","its","now","find","long","down","day","did","get","come","made","may","part"};


Remember that you can use compareTo with Strings, "and".compareTo("had") will return a negative value. You could add Strings, one at a time, in order to a new ArrayList, removing them from the old list as they are moved. Or, another approach, find the smallest (earliest) word in the alphabet and move it to the front of the ArrayList, using .remove and .set.

Try your methods with a small group of words, numbering maybe 5, so you can see the progress.
