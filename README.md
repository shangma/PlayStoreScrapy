PlayStoreScrapy
===============

A showcase of Google PlayStore Scraper built on top of Python + Scrapy Framework.

It will scrape the android apps data into CSV file based on search keyword inputs.

Requirements
============

 * [Python v2.7.x][1] (Python v3.x is not supported yet)
 * [Scrapy][2]


How to run
==========

    $ cd PlayStoreScrapy
    $ scrapy crawl playstorescrapy -a keywords=<your_keywords>

You can also supply multiple keywords separated by comma:

    $ scrapy crawl playstorescrapy -a keywords=browser,game,chat

Additional options:

    -a max_item=<number>          Specify maximum number of scraped items (default=0)
    -a output=<filename>          Specify output filename path (default=item.csv)
    -a download_delay=<number>    Specify download delay in seconds (default=0)
    -a email=<email>              Specify login email
    -a "password=<password>"      Specify login password (note: the double-quotes is required)

# About Me

My name is Suyandi. I'm a software engineer and web scraping specialist.

# Contact

![untitled-2.png](http://i57.tinypic.com/30bfi1e.jpg)

  [1]: https://www.python.org/downloads/
  [2]: http://scrapy.org/
