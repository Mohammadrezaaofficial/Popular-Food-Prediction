# Popular-Food-Prediction

## Summary
The document describes an analysis of simulated customer order data to identify the most popular food items for four different fictional shops: "Pizza Hub," "Sushi World," "Burger Town," and "Healthy Bites." The project's goal is to provide business insights that can be used for marketing, such as highlighting best-selling items, recommending products to new customers, and creating promotions.

## 1. Importing Libraries
The analysis begins by importing essential Python libraries: pandas for data manipulation, numpy for numerical operations, and matplotlib.pyplot and seaborn for data visualization.

## 2. Creating a Sample Dataset
To simulate a real-world scenario, a dataset is created with 1000 random orders. The data includes the following columns: order_id, shop_id, customer_id, food_item, and quantity. The data is designed to have a realistic distribution of orders across the four shops.

## 3. Data Aggregation
The next step involves aggregating the data to determine the total quantity of each food item ordered across all shops. This is done by grouping the data by shop_id and food_item and then summing the quantity.

## 4. Identifying Top Foods
The document then identifies the top 4 most popular food items for each shop. This is achieved by sorting the aggregated data in descending order of quantity and selecting the top entries for each unique shop_id.

## 5. Visualization
To visualize the findings, two plots are created:

A bar chart that shows the total quantity of the top 4 food items ordered across all shops. This gives a broad overview of overall popularity.

A scatterplot that displays the total quantity of orders for each food item.

## 6. Shop-Level Insights
The document concludes with a section that prints a list of the top 4 most popular foods for each individual shop, providing specific, actionable insights. For example, it shows that for "Pizza Hub," the top food is "Pepperoni" and for "Healthy Bites" it's "Avocado Toast."

## Conclusion
The document successfully demonstrates a data analysis workflow to extract valuable business insights from a sales dataset. By following the steps of data creation, aggregation, and visualization, it effectively identifies the top-selling products for each shop. This information can be directly applied to business strategies such as promotions and targeted recommendations. The analysis is complete and presents a clear, actionable outcome.
