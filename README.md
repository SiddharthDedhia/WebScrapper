# WebScrapper

Web scraping is a technique using which the webpages from the internet are fetched and parsed to understand and extract specific information similar to a human being. 

Application :

WebScrapper for extracting reviews of E-commerce products.

Use Case :

Helps the customer make a better decision by showing all product reviews.

Application Architecture :

The flask application extracts reviews of different product from an Indian E-Commerce Website known as 'Flipkart'.
The user enters the keyword to search.The application queries the MongoDB database to search if the product reviews are already available in the database.

If Yes, displays the reviews to the customer on a web page.

If No,the application searches the internet for the reviews and inserts them into the MongoDB database.Then the reviews are displayed to the customer on a web page. 

