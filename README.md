# article_scraper
This works as a webpage scraped desinged to work with google search results and read the returned pages.
It uses sereveral libraries and the GloVe vector data. The GloVe data can be downloaded here https://nlp.stanford.edu/projects/glove/
It also requires a web-driver to work with Selenium. Currently it calls the Chrome driver but could be modified to use a different one.
Web-Drivers can be found here https://www.seleniumhq.org/projects/webdriver/

After gathering and reading the results the text is analysed to return summaries of the content following a guide found here https://www.analyticsvidhya.com/blog/2018/11/introduction-text-summarization-textrank-python/

A word cloud is incouded as a consise at a glance interpritation but the results are often more intuitive since they are based on results from a search term.
