# Web Scraping - Shopify
<p align="center">
  <img width="400" height="300" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSYAhiZBTeLXMvHtO4VDY42k8zngE5F8-Xdv_ZVnx1uBUhAnS6nDnglgtoXAUNdk1G7tLo&usqp=CAU">
</p>
Shopify Inc. is a Canadian multinational e-commerce company headquartered in Ottawa, Ontario. It is also the name of its proprietary e-commerce platform for online stores and retail point-of-sale systems. The Shopify platform offers online retailers a suite of services including payments, marketing, shipping and customer engagement tools. The company reported that it had more than 1,700,000 businesses in approximately 175 countries using its platform as of May 2021. According to BuiltWith, 1.58 million websites run on the Shopify platform as of 2021. According to W3Techs, 4.4% of the top 10 million websites use Shopify. The total gross merchandise volume exceeded US$61 billion for calendar 2019. As of 2022, Shopify is among the top 10 largest publicly traded Canadian companies by market capitalization. Total revenue for the full year 2021 was US$4.611 billion.

# What is Web Scraping?
Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites. Web scraping a web page involves fetching it and extracting from it. Fetching is the downloading of a page (which a browser does when a user views a page). Therefore, web crawling is a main component of web scraping, to fetch pages for later processing. Once fetched, then extraction can take place. The content of a page may be parsed, searched, reformatted, its data copied into a spreadsheet or loaded into a database. Web scrapers typically take something out of a page, to make use of it for another purpose somewhere else. An example would be to find and copy names and telephone numbers, or companies and their URLs, or e-mail addresses to a list (contact scraping).

# Web Scraping Techniques
In general, there are two ways you can do this:
- Manual: a method where you copy data by copy-pasting from a website
- Automatic: a method that uses code, an application, or a browser extension.

Web scraping is now made easier with the help of browser extensions and applications. There are six commonly used web scraping techniques, namely:
1. Copying data manually
2. Using regular expressions
3. HTML parse
4. Analyze DOM
5. Using XPath
6. Using Google Sheets

# Benefits and Problems of Web Scraping
Following are the four main advantages:
1. Getting Leads
2. Comparing Massive Data
3. Optimization of Reviews, Product Pricing and Service
4. Looking for Company Information

Although web scraping is a very helpful technique in extracting site data, there are also problems to its implementation. At least, the following five things you need to remember if you want to do it:
1. No web scraping technique is 100% effective
1. The data obtained is not always neat
1. Understanding of the structure of the website page remains an obligation
1. Your access to a website may be blocked
1. Not all websites are easy to extract data

# About The Project
The main goal of this project is to get data from the Shopify site on product names, types, prices, weights, and other attributes. The data is then stored in a data frame and exported to an excel or CSV file type dataset.

# Built with
- [**pandas**](https://pandas.pydata.org/)
- [**NumPy**](https://numpy.org/)
- [**json**](https://docs.python.org/3/library/json.html)
- [**urlib**](https://docs.python.org/3/library/urllib.html#module-urllib)
- [**request**](https://docs.python-requests.org/en/latest/)

# Getting Started
requests allows you to send HTTP/1.1 requests extremely easily. There’s no need to manually add query strings to your URLs, or to form-encode your POST data. Keep-alive and HTTP connection pooling are 100% automatic, thanks to urllib3.

Read more for [**json encoder and decoder documentation**](https://docs.python.org/3/library/json.html), [**urllib documentation**](https://docs.python.org/3/library/urllib.html#module-urllib) and [**Request documentation**](https://docs.python-requests.org/en/latest/)
### **Prerequisites**
Here is how to run the library used in this project. First Install the list of libraries below on your device or kernel:
- json <br>
  ```
  pip install jsons
  ```
- urllib <br>
  ```
  pip install urllib3
  ```
- request <br>
  ```
  pip install requests
  ```
