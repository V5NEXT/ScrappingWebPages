# ScrappingWebPages
How to scrape web pages using BeautifulSoup

This is a beginners tutorial on how to scrape webpages.
Scraping is an important asset if you are into Data Science as more on cases we doesnt have access to dataset and we need to scrape our way through.

In this Tutorial we would be using BeautifulSoup for scrapping newspapers, https://www.crummy.com/software/BeautifulSoup/bs4/doc/

We will scrape two different newspapers(so that we can some visible differences)

Daily Mail (https://www.dailymail.co.uk/home/index.html)
NBC (https://www.nbcnews.com/)

Another important alternative for scrapping is the use of inbuild api's, like the once provided by NYT
https://developer.nytimes.com/docs/archive-product/1/overview

We need to create an account inside the NYT Developer portal and generate an api key which can be then used for accessing the data archives from any programming base.

https://api.nytimes.com/svc/archive/v1/2019/1.json?api-key=yourkey

enter your key at the 'yourkey' section.

You can also sort the news issues by year. The Archieve feature of NYT gives us the access of news form 1851.
