# Scraping-tables-from-web-Pages-using-R
A simple repository showing how to extract data from tables in web pages
# Web Scraping Data From Tables in Web Pages

>- Most of the times you may be looking forward to get data from the web but it is existing in table format
>- You can choose to copy-paste which is tendious and also time-consuming. Another drawback of copy-pasting, is that you are likely to lose some of the information along the way
>- Fortunately, you can ease all the work by obtaining the entire tables from the web pages by performing simple scraping

We will be focusing with the `rvest` package which is core in performing web scraping

>- We will be scraping tables from Wikipedia page [Premier League](https://en.wikipedia.org/wiki/Premier_League) 
>- One major challenge with web scraping is that websites are prone to changes, fortunately, Wikipedia changes doesn't alter the structure of the page and that why it will be used.
>- We will clean the data for the **Top Ten Premier League Players** with the highest transfer fee
