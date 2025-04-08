# 🍽️ FoodHub Data Analysis — Python Foundations Project

## 📌 Overview

**FoodHub** is a food aggregator app connecting customers with multiple restaurants and delivery services in New York. With a rapidly growing number of orders, FoodHub aims to analyze its order data to enhance customer experience, understand restaurant demand, and optimize delivery operations.

This project performs an end-to-end data analysis using Python to extract insights from historical order data stored in the FoodHub system.

---

## 🎯 Objective

As a Data Scientist at FoodHub, your goal is to analyze the food order dataset to answer key business questions. The analysis will help the company:
- Understand customer preferences
- Evaluate restaurant and cuisine demand
- Identify bottlenecks in food preparation and delivery
- Improve delivery experience and rating outcomes

---

## 🧾 Dataset Description

The dataset contains detailed records of customer orders made through the FoodHub app.

| Column Name            | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `order_id`             | Unique identifier for each order                                            |
| `customer_id`          | ID of the customer who placed the order                                     |
| `restaurant_name`      | Name of the restaurant fulfilling the order                                 |
| `cuisine_type`         | Type of cuisine ordered                                                     |
| `cost_of_the_order`    | Total cost of the order in USD                                              |
| `day_of_the_week`      | Indicates whether the order was placed on a weekday or weekend             |
| `rating`               | Customer rating for the order (out of 5)                                    |
| `food_preparation_time`| Time (in minutes) taken to prepare the food                                 |
| `delivery_time`        | Time (in minutes) taken to deliver the food after pick-up                   |

---

## 🛠️ Tools & Technologies

- **Python 3.x**
- **Pandas** for data manipulation
- **Matplotlib / Seaborn** for visualization
- **Jupyter Notebook** (or any Python IDE)
- Optional: **NumPy**, **SciPy**, or **Plotly** for deeper insights

---

## 📊 Key Questions to Answer

- Which restaurants receive the most orders?
- What are the most popular cuisines?
- How do preparation and delivery times vary by restaurant or day of the week?
- How does order cost relate to customer ratings?
- What factors affect high or low delivery ratings?
- Are there delays during weekends compared to weekdays?

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/foodhub-data-analysis.git
   cd foodhub-data-analysis

