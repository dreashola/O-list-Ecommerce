# Project Name: Brazilian E-commerce O-list Report
________________________________________
## Project Objective: What is the status of the business in terms of performance?
________________________________________
## Data Sourcing
Data was sourced from: 
- Mode Public Warehouse [brooklyndata](mode.com) but can alternatively be downloaded from [kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- [Brazil-Help](https://brazil-help.com/brazilian_states.htm)
________________________________________
## Data Transformation



A data model was created consisting of nine tables: Reviews, Locations, Orders, Ordered Items, Payments, Sellers, Customers, Calendar and Products. Each table underwent a series of transformations to clean and structure the data appropriately.

- Duplicate records and unneccesary columns were removed.
- Accented characters were replaced with their unaccented equivalents where appropiate.
- The  data about states was expanded using data from [Brazil-Help](https://brazil-help.com/brazilian_states.htm)
- Certain substrings or word patterns were replaced or removed.
- Review titles and comments were translated from Portugese to English using Google Translate API.

________________________________________
## Key Insights

1. **Order Volume and Value Trends:**
   - Initial entry period in the market (last quarter of 2018) saw low order volume and value.
   - Steady growth observed until August 2018, followed by a sharp decline. Further investigation is required to determine the cause of this decline.

2. **Product Category Performance:**
   - "Health & Beauty" and "Furniture" emerge as leading product categories in terms of order value.

3. **Geographical Performance:**
   - Sao Paulo stands out as the top location in terms of order value and volume.

4. **Order Cancellation Rate:**
   - A significant drop in cancellation rate from 50% in September 2016 to negligible until September 2018, followed by an unusual spike. Further analysis is required to understand the cause.

5. **Order Delivery Performance:**
   - Impressive order delivery performance with 97% of orders being delivered promptly. Minimal cancellation (0.63%) and unavailability (0.61%).

6. **Customer and Seller Base Growth:**
   - The platform has successfully expanded its customer base to over 96,000 and seller base to over 3,000.

7. **Reviews and Sales Relationship:**
   - Positive reviews correlate with product names' length. Further investigation is needed to understand the underlying dynamics.

8. **Customer Satisfaction:**
   - Positive reviews highlight keywords such as "congratulations," "beautiful," "schedule," suggesting opportunities to enhance customer satisfaction through timely deliveries and product quality improvements.

9. **Customer Criticisms:**
   - Negative reviews emphasize concerns like "defective," "refund," "delay," indicating a need for surveys to understand customer sentiments and address issues promptly.

10. **Average Order Composition:**
    - Customers place an average of 1.13 products in each order.

11. **Geographic Customer Distribution:**
    - Majority of customers reside in Sao Paulo, highlighting a potential market dominance. Rio de Janeiro follows but with significantly fewer customers.

12. **Delivery Time Analysis:**
    - Average delivery time increases with distance from Sao Paulo, suggesting a need for further analysis and surveys to assess potential benefits of having warehouses in other states.

13. **Unavailability Rates:**
    - Declining unavailability rates, reaching an all-time low of 0.11% in August 2018.

14. **Seller Distribution:**
    - Over 50% of all sellers are located in Sao Paulo state, with the majority residing in Sao Paulo city.
________________________________________
## Recommendations

1. Conduct an in-depth analysis to determine the cause of the sharp decline in orders since August 2018.

2. Explore strategies to capitalize on the success of "Health & Beauty" and "Furniture" categories.

3. Investigate the cause behind the spike in the order cancellation rate in September-October 2018.

4. Implement initiatives to maintain and potentially improve the impressive delivery performance.

5. Leverage the positive correlation between product name length and order success and assess strategies to optimize product naming.

6. Initiate surveys to gather customer feedback on products and services, addressing negative sentiments raised in reviews.

7. Consider geographical expansion or warehouse placement in states with a significant customer base to reduce delivery times.

8. Explore opportunities to further grow the customer and seller base in key regions.
