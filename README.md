# Web-Scraping-Watch-Data-
Extracting the data of all the men's watches from WorldOfWatches.com website

The main aim behind extracting the watch data is to use it and create a watch recommendation engine using Machine Learning.
The approach I used was, first I extracted all the watch brand names and their respective web links. Then I iterated through each link and extracted the page urls under each brands. For example Fossil have 6 pages of watches with 24 watches on each page then first I extracted the 6 pages url and stored it in a dataframe.
Using the Page Url data frame I wrote a code which iterates through each page url and extracts the link of each and every watch on the worldOfWatches website. So basically I had links of all the 4800 watches in a dataframe.
Next task was to iterate through each watch link and extract all the 38 features. This was done using nested for loops. This code takes a lot of time to run (Around 9 hrs) because of nested loops, however I will try to make it a bit faster. 
