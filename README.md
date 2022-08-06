# DND 5e Spell Scrapper

Instructions:

* Get all spell URLs with an xpath plugin and the following query. ```//div[@class="list-pages-box"]//a/@href```
They are stored in urls.txt
* Run the notebook "Scrapping.ipynb" to scrap every url.
* Run the notebook "Parsing.ipynb" to parse the information into a DataFrame.
