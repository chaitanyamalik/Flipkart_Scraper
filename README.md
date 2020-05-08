# Flipkart_Scraper
In this project, I've recreated the Flipkart search box.
When the user searches for a product/category in the box:-

1. First, the program scrapes all products displayed on the first page of the results using BeautifulSoup and takes out relevant information.

2. Each product has a link which directs to it's product page. The program then opens each link and scrapes reviews for each product.(BeautifulSoup)

3. The data is stored in a SQL Database using sqllite3 (Here by the name of FLIPKART).

4. The program fetches data from the database and the user is able to traverse through the data using the UI built from Tkinter.

5. Data Analysis is performed using Seaborn
