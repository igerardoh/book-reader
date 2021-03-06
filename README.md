# Book Reader

### Description :

This project contains a file reader algorithm capable of reading multiple files contained inside of a folder to later extract every unique word with its frequency. This data is collected and stored in a dataframe using the pandas library. This algorithm uses several books files in a .txt format extension. 

The final result is a scatter plot created with the matplotlib library. This scatter plot is helpful to visualize the relation between the unique words and the total amount of words contained in every book by different languages.

![scatter_plot](https://github.com/igerardoh/book-reader/blob/master/total_vs_unique_words.png "relation between unique words and total amount of words")

For extra details, this algorithm also output a .txt file containg the frequency of every unique word by language, author, and book title.

### DEPENDENCIES :
  - os
  - pandas
  - time

### TO-DO :

  - ~~Iterate and read all the files through every subfolder.~~
  - ~~Count the number of unique words by file.~~
  - ~~Count every word's frequency by file.~~
  - ~~Visualize the results by language.~~