# Capstone-Project
SHOE BRAND CAPSTONE Project

1. **Web Scraping:** Extracted shoe data from specified URLs using BeautifulSoup and Selenium.
2. **SQL Queries:** Created CSVs and write SQL queries for specific insights.
3. **EDA:** Merged CSVs with pandas, and analyze data using stats and visualizations.
4. **Machine Learning:** Predicted shoe prices and star ratings using regression and classification models. Apply scaling and hyperparameter tuning. Save the best models on GitHub. Follow the submission guidelines carefully.


Web scrapping :
1. https://www.nike.com
2. https://www.adidas.com
3. https://us.puma.com/us/en
4. https://www.skechers.com
5. https://www.columbia.com/
6. https://www.woodlandworldwide.com/

## Phase 2 
table in  csv format  (3 csv files)  

1. **Table1.csv:** ShoeName ,Category(Men/Women), no.of colors,price  
2. **Table2.csv:** count of sizes, colors 1, color 2, color3 ,color4, color5, Style code/product code  
3. **Table3.csv:** reviews, Size, comfort, durability /quality/performance(quantification), star rating

## SQL queries :

1. **Table 1**          
  * query  to retrieve all shoe names and their corresponding prices for men's shoes:
  * query to retrieve the number of different colors available for each category.
  * query to find the most expensive men's shoe.
  * query to find the cheapest women's shoe in a specific color (e.g., 'Black ').
  * query to retrieve all shoe names and their corresponding prices for men's shoes.

2. **Table 2**
  * query that retrieves the count of sizes for all styles.
  * query to list all styles with their associated colors.
  * styles that have more than one color.
  * query to find the count of sizes available for each color for a specific style code.
  * query to find styles that have a specific color.

3. **Table 3**
  * query that calculates the average comfort rating for a specific product based on its reviews.
  * query to retrieve products with high star ratings (e.g., 4 stars or above)
  * query that counts the number of reviews for each product.
  * retrieved products that have a quantified durability/quality/performance rating above a certain threshold (e.g., above 7).
  * query that  calculates the average comfort rating for each size.

**7  Joined SQL Queries  using all 3 tables**
  * query to find the top-rated men's shoes along with their sizes from "Table1" and "Table3."
  * query that calculates the average comfort rating for each category from "Table1" and "Table3."
  * query that identifies products with a durability/quality/performance rating higher than the average from "Table1" and "Table3."
  * subquery that finds products with comfort ratings above the average comfort rating using "Table1" and "Table3."
  * query that joins Table 1  and Table 2  using the "Style code/Product code" column, allowing you to retrieve shoe information along with product details.
  * query that  identifies products with a star rating above the average star rating for their respective size.
  * query that finds products with the highest comfort rating in each category.

## Phase  3
* dataframe of 3 CSV files using the concat/merge /join operation of pandas and start doing EDA.
* EDA in detail to explore the insights of data and write the detailed observations of each analysis.

## Phase 4
Machine learning code to make predictions of price and star rating. :
* price
* star rating.























 



 



 

