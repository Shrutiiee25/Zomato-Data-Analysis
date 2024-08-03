# Zomato-Data-Analysis
## Project Description

This project involves the cleaning, visualization, and analysis of restaurant data from Zomato. The dataset contains information about various restaurants, including their location, cuisine type, ratings, and more. The primary objective is to provide insights into the dining trends and preferences in the Banashankari area.

## Dataset
Dataset Link : https://www.kaggle.com/datasets/rajeshrampure/zomato-dataset 

The dataset contains the following fields:
- *url*: The URL of the restaurant's Zomato page.
- *address*: The physical address of the restaurant.
- *name*: The name of the restaurant.
- *online_order*: Indicates if the restaurant accepts online orders.
- *book_table*: Indicates if the restaurant allows table booking.
- *rate*: The average rating of the restaurant.
- *votes*: The number of votes received by the restaurant.
- *phone*: Contact number of the restaurant.
- *location*: The specific location of the restaurant.
- *rest_type*: The type of restaurant (e.g., Casual Dining, Cafe).
- *dish_liked*: Popular dishes at the restaurant.
- *cuisines*: The type of cuisine offered by the restaurant.
- *approx_cost(for two people)*: The approximate cost for two people.
- *reviews_list*: List of reviews received by the restaurant.
- *menu_item*: Items on the menu.
- *listed_in(type)*: Type of listing (e.g., Buffet, Cafes).
- *listed_in(city)*: The city where the restaurant is located.

## Data Cleaning

Data cleaning steps performed:
1. Removed duplicate entries.
2. Handled missing values by either filling them with appropriate values or removing the rows/columns.
3. Standardized the format of phone numbers and addresses.
4. Ensured consistency in the naming conventions for restaurants and cuisines.

## Data Visualization

Several visualizations were created to understand the data better:
1. *Distribution of Ratings*: A histogram showing the distribution of restaurant ratings.
2. *Popular Cuisines*: A bar chart representing the most popular cuisines in Banashankari.
3. *Online Orders and Table Booking*: Pie charts showing the proportion of restaurants that accept online orders and table bookings.
4. *Cost Analysis*: A box plot depicting the distribution of costs for two people across different restaurants.

## How to Use

1. *Clone the repository*:
   bash
   git clone https://github.com/yourusername/zomato-restaurant-analysis.git
   

2. *Navigate to the project directory*:
   bash
   cd zomato-restaurant-analysis
   

3. *Install the required dependencies*:
   bash
   pip install -r requirements.txt
   

4. *Run the Jupyter Notebook*:
   bash
   jupyter notebook python_project_3_Zomato.ipynb
   

## Results

The analysis provides several insights into the dining preferences in Banashankari:
- Most restaurants have a rating between 3.5 and 4.0.
- North Indian and Chinese cuisines are the most popular.
- A significant number of restaurants offer online ordering and table booking services.
- The cost for two people varies widely, with some upscale restaurants charging significantly more.

## Conclusion

This project demonstrates the importance of data cleaning and visualization in extracting meaningful insights from raw data. The findings can help restaurant owners, food bloggers, and diners make informed decisions about dining in Banashankari.
