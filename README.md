# Data-Analytics-Project
Zomato Data Analysis Project

# Zomato Data Analysis Project

## Overview

This project analyzes restaurant data from Zomato to uncover customer preferences, restaurant popularity, and ordering behavior. Using Python and visualization libraries, the project answers six key business questions that can help Zomato optimize its platform and marketing strategies.

---

## Dataset Description

The dataset contains 148 restaurant entries with the following columns:

- `name`: Restaurant name  
- `online_order`: Whether online ordering is available  
- `book_table`: Whether table booking is available  
- `rate`: Customer rating (converted to float)  
- `votes`: Number of votes received  
- `approx_cost(for two people)`: Estimated cost for two people  
- `listed_in(type)`: Type/category of restaurant (e.g., Buffet, Cafes, Dining)

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook

---

## Business Questions & Insights

### 1️⃣ What type of restaurant do the majority of customers order from?

- **Visualization**: Countplot of `listed_in(type)`
- **Insight**: Most restaurants fall under the **Dining** category, indicating it's the most common type.

---

### 2️⃣ How many votes has each type of restaurant received from customers?

- **Visualization**: Line plot of total votes grouped by restaurant type
- **Insight**: **Dining** restaurants received the highest number of votes, making them the most popular.

---

### 3️⃣ What are the ratings that the majority of restaurants have received?

- **Visualization**: Histogram of `rate`
- **Insight**: Most restaurants have ratings between **3.5 and 4.0**, suggesting generally favorable customer experiences.

---

### 4️⃣ Zomato has observed that most couples order food online. What is their average spending on each order?

- **Visualization**: Countplot of `approx_cost(for two people)`
- **Insight**: Majority of couples prefer restaurants with an average cost of **₹300**, indicating budget-friendly choices.

---

### 5️⃣ Which mode (online or offline) has received the maximum rating?

- **Visualization**: Boxplot comparing `rate` across `online_order` values
- **Insight**: Restaurants that accept **online orders** tend to have **higher ratings** than those that don't.

---

### 6️⃣ Which type of restaurant received more offline orders, so Zomato can provide those customers with offers?

- **Visualization**: Heatmap of restaurant type vs. online order preference
- **Insight**:  
  - **Dining** restaurants receive more **offline orders**  
  - **Cafes** receive more **online orders**  
  - Zomato can target **Dining** restaurants for offline offers and **Cafes** for online promotions.

---

## 🚀 How to Run

1. Clone this repository  
2. Open `Zomato_Project.ipynb` in Jupyter Notebook  
3. Run all cells to view the analysis and visualizations

---

## 📬 Contact

For feedback or collaboration, feel free to reach out via GitHub or connect with me on [LinkedIn](https://www.linkedin.com/in/divesh-sonawane-6ba631297).
