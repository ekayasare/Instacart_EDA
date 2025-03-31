# TripleTen Sprint 3 Project – EDA

This was my second project in the TripleTen Data Science program, and honestly, it was such a fun experience. I had more independence this time around, which helped me start finding my rhythm as a data scientist.

### Instacart Orders – Shopping Habits Uncovered

The goal of this project was to explore and analyze customer shopping patterns using real-world data from Instacart. I cleaned the data, merged multiple sources, and dug into user behavior with the help of visualizations and pivot tables.

#### The Data

The dataset was based on a modified version of Instacart’s 2017 Kaggle competition data, spread across five CSV files:

- **`instacart_orders.csv`**: Each row is a single order on the app.
  - Includes `order_id`, `user_id`, `order_dow` (day of week), `order_hour_of_day`, and `days_since_prior_order`.
- **`products.csv`**: Info about each product.
  - Contains `product_id`, `product_name`, `aisle_id`, `department_id`.
- **`order_products.csv`**: Details of each item in each order.
  - Includes `add_to_cart_order` and `reordered` flags.
- **`aisles.csv`** and **`departments.csv`**: Helpful lookup tables for categorizing products.

#### The Process

I started with data cleaning and preprocessing—checking for missing values (like in `days_since_prior_order`) and ensuring all the data types made sense. After that, I merged everything into a unified dataset so I could start digging into the patterns.

I looked at:

- When customers shop (by hour and day)
- How frequently they reorder items
- Which items and departments are the most popular
- How big their average carts are

Visualizations really helped to highlight these trends—like peak shopping hours, top reordered products, and department breakdowns.

### Results & Takeaways

This project helped me flex both my data wrangling and storytelling skills. I wrote up detailed markdowns for each step of the project, which was a big step forward for me in terms of communication.

I wrapped it all up with a clear conclusion that summarized the key findings and even gave a few strategic suggestions for Instacart—like doubling down on promotions during peak hours or focusing retention efforts on users who reorder frequently.
