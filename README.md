# E-Commerce-Sales-Customer-Insights-Dashboard

🔹 Goal:
Create a visually compelling dashboard to monitor sales performance, customer retention, product trends, and profitability across time, channels, and categories.

# We are using the faker library to generate the fake data  which looks so much real for the analysis.

🔮 What is Faker doing?

The Faker library is used to generate realistic-looking fake data, like names, dates, and locations. It's super handy for testing and projects where you need sample data that feels real.

In this code, Faker is generating:

Random regions/states for customers (fake.state())

Random signup dates within the last 2 years (fake.date_between(start_date='-2y', end_date='today'))

Random order dates for the last year (same function)
