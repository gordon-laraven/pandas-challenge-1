## pandas-challenge-1

## Part 1: Explore the Data
# Import the data from the CSV file.
# View the column names.
# Use the describe function to gather some basic statistics.
# What three item categories had the most entries?
# For the category with the most entries, which subcategory had the most entries?
# Which five clients had the most entries in the data?
# Store the client ids of those top 5 clients in a list.
# How many total units (the qty column) did the client with the most entries order?

## Part 2: Transform the Data
# Create a column that calculates the subtotal for each line using the unit_price and the qty.
# Create a column for shipping price. Assume a shipping price of $7 per pound for orders over 50 pounds and $10 per pound for items 50 pounds or under.
# Create a column for the total price using the subtotal and the shipping price along with a sales tax of 9.25%.
# Create a column for the cost of each line using unit cost, qty, and shipping price (assume the shipping cost is exactly what is charged to the client).
# Create a column for the profit of each line using line cost and line price.

## Part 3: Confirm Your Work
# Order ID 2742071 had a total price of $152,811.89 Order ID 2173913 had a total price of $162,388.71 Order ID 6128929 had a total price of $923,441.25
# Confirm that your calculations match the receipts. Remember, each order has multiple lines.

## Part 4: Summarize and Analyze
# Use the new columns with confirmed values to find the following information.
# How much did each of the top 5 clients by quantity spend? Use your work from Part 1 for client ids?
# Create a summary DataFrame showing the totals for the top 5 clients with the following information: total units purchased, total shipping price, total revenue, and total profit.
# Create a function to change the currency to millions of dollars. Format the data and rename the columns to names suitable for presentation. Then, sort the DataFrame in descending order by total profits.
# Write a brief 2-3 sentence summary of your findings.