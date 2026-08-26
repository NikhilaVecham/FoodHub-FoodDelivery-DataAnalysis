# 🍽️ FoodHub – Food Delivery Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on FoodHub's food delivery order data to understand customer ordering behavior, restaurant performance, cuisine preferences, delivery efficiency, and revenue opportunities.

The objective is to transform raw order data into **actionable business insights** that can help FoodHub improve customer experience and operational performance.

## 🎯 Business Objective

FoodHub connects customers with multiple restaurants through its online food delivery platform.

The analysis focuses on answering key business questions such as:

* Which restaurants and cuisines receive the most orders?
* How do delivery times differ between weekdays and weekends?
* Which restaurants qualify for promotional opportunities?
* Which cuisines offer higher revenue potential?
* How much revenue does FoodHub generate from commissions?
* What factors influence customer ratings and satisfaction?

## 📊 Dataset

The dataset contains **1,898 food orders with 9 features**.

Key variables include:

* `order_id`
* `customer_id`
* `restaurant_name`
* `cuisine_type`
* `cost_of_the_order`
* `day_of_the_week`
* `rating`
* `food_preparation_time`
* `delivery_time`

## 🔍 Exploratory Data Analysis

The project includes both **univariate and multivariate analysis** to explore customer, restaurant, order, and delivery patterns.

### Key Findings

* **American** and **Japanese** are among the most popular cuisines.
* **Shake Shack** received the highest number of orders.
* Approximately **29.24%** of orders cost more than $20.
* Average food preparation time is approximately **27.4 minutes**.
* Weekday deliveries average **28.34 minutes**, compared with **22.47 minutes** on weekends.
* Approximately **10.54%** of orders take more than 60 minutes from preparation through delivery.
* **736 orders** did not receive a customer rating.
* French, Southern, and Thai cuisines have relatively high average order costs.

## 🏆 Top Restaurants

The five restaurants receiving the highest number of orders were:

1. Shake Shack
2. The Meatball Shop
3. Blue Ribbon Sushi
4. Blue Ribbon Fried Chicken
5. Parm

Restaurants meeting FoodHub's promotional criteria of **more than 50 ratings and an average rating greater than 4** were:

* Blue Ribbon Fried Chicken
* Blue Ribbon Sushi
* Shake Shack
* The Meatball Shop

## 💰 Revenue Analysis

FoodHub earns commission from restaurant orders based on order value:

* **25% commission** for orders above $20
* **15% commission** for qualifying orders above $5

Based on these rules, the calculated net revenue across the analyzed orders was approximately **$6,166.30**.

## 📈 Customer & Operational Insights

### Delivery Performance

Delivery times are significantly higher on weekdays than weekends.

This suggests an opportunity to improve weekday logistics through better delivery-partner allocation and route optimization.

### Customer Satisfaction

Ratings were generally high across cuisine types.

The analysis also showed no strong relationship between delivery time or food preparation time and customer ratings, suggesting that customer satisfaction may depend on multiple factors beyond delivery speed alone.

### Cuisine Performance

American and Japanese cuisines show strong customer demand, particularly during weekends.

French, Southern, and Thai cuisines have higher average order values and therefore represent potential premium revenue opportunities.

## 💡 Business Recommendations

### 1. Optimize Weekday Deliveries

Increase delivery-partner availability and improve route planning during weekday peak periods to reduce the gap between weekday and weekend delivery times.

### 2. Promote Premium Cuisines

Feature French, Southern, and Thai restaurants through targeted promotions, bundles, and upselling strategies to increase average order value.

### 3. Capitalize on Weekend Demand

Run targeted promotions for high-demand American and Japanese cuisines while ensuring sufficient delivery capacity during weekend peaks.

### 4. Improve Customer Feedback Collection

Introduce post-delivery reminders or simplified rating workflows to reduce the large number of unrated orders and collect better customer-experience data.

## 🛠️ Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook / Google Colab**

## 🚀 Project Workflow

**Business Understanding → Data Understanding → Data Cleaning → Univariate Analysis → Multivariate Analysis → Customer Analysis → Restaurant & Cuisine Analysis → Revenue Analysis → Business Insights → Recommendations**

## 🎯 Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Data Manipulation with Pandas
* Statistical Analysis
* Data Visualization
* Customer Behavior Analysis
* Revenue Analysis
* Business Insight Generation
* Data-Driven Decision Making

### Project Type

**Data Analytics | Exploratory Data Analysis | Python | Business Analytics | Food Delivery Analytics**

---

## 🧠 Author

**Nikhila Vecham**
AI/ML Engineer | Machine Learning | Generative AI | Data Science


