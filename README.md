# Class_for_scraping
 The utils.py file has the following classes/functions defined:
1. Scrape_All class, which will scrape from a given page all:
a. hyperlinks (<a>) and provide the absolute link if relative one is given in the page,
b. headings and paragraphs and merge them inside one string with a new line between different headings/paragraphs, without distorting order).
c. custom tags provided by the user (i.e. if the user provides li.author or similar input then all the list items that have class author must be scraped.
 #Super_list class, which will take a list as input and provide the following functionalities:
a. untilst function, that will return the unlisted version of a nested list or the same one if list was not nested,
b. merge function, that will merge all the elements of any list into strings,
c. find function that will take a type argument as an input. If type =:
i. number, then it will return all the list elements that include a number,
ii. letter, then it will return all the list elements that include a letter.
#Cleaner class, which will take a string as an input and provide the following methods:
a. tokenize into words/sentences,
b. lemmatize, clean stopwords,
c. make plural/singular,
d. uppercase/lowercase,
e. draw frequency distributions of words.
4. (0.5 points) Use utils.py, Wikipedia API and a sample Wikipedia article to test my objects/methods..
