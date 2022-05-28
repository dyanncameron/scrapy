# scrapy
scraping book list

A bit of instruction how I created the project and how to run it

install python3 -m venv venv for its virtual environment folder

to activate venv, type-in on the terminal source venv/bin/activate

I added to the python select interpreter the venv environment 

install scrapy using terminal - pip install scrapy 

create a project name on the terminal - scrapy startproject bookscraper

inside the bookscraper folder I created books_spider.py file inside the spider folder

I based the code from the scrapy documentation and just change the urls and class names

to run the project using the terminal - scrapy crawl books

after running the code there should be HTML file added on the bookscraper folder name booklist-index.html where you can see all the books category list 
