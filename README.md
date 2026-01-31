# Food Delivery Data Analysis

This project analyzes food delivery platform data by integrating multiple real-world data formats including CSV, JSON, and SQL. The objective is to build a unified dataset and extract meaningful business insights using Python.

This project was completed as part of a data analysis hackathon/assessment.



## Datasets Used

The analysis is based on the following datasets:

- orders.csv  
  Contains transactional order data such as order ID, user ID, restaurant ID, order date, and total order amount.

- users.json  
  Contains user master data including user details and membership type (Gold or Regular).

- restaurants.sql  
  Contains restaurant master data including restaurant name, city, cuisine type, and restaurant ratings.



## Tools and Technologies

- Python  
- Pandas  
- SQLite  
- Google Colab  
- GitHub  



## Data Processing Steps

1. Loaded CSV data using pandas
2. Loaded JSON data and normalized it into tabular format
3. Loaded SQL data into an in-memory SQLite database
4. Merged all datasets using left joins to retain all orders
5. Created a final consolidated dataset for analysis



## Analysis Performed

The final dataset was used to analyze:

- Order trends over time  
- City-wise revenue distribution  
- Comparison of Gold and Regular member behavior  
- Cuisine-wise performance and average order value  
- Relationship between restaurant ratings and revenue  



## How to Run the Notebook

1. Open the notebook `food_delivery_analysis.ipynb`
2. Upload the files `orders.csv`, `users.json`, and `restaurants.sql`
3. Run all cells sequentially



## Author

Sanjana L  
GitHub: https://github.com/SanjanaL12



## Notes

This project is intended for educational and evaluation purposes.
