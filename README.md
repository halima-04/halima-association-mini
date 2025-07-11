# halima-association-mini

## 🛒 Association Rule Mining Mini Project

### 🎯 Objective

Simulate basic transactional data and use **association rules** to uncover shopping patterns using the **Apriori algorithm**.

---

## 📌 Tasks

### 1. Simulate Transaction Data (3 Marks)
- Generated 10 fake transactions.
- Each transaction contains 2–5 items randomly selected from a pool of 8 unique items:
  - `Bread, Milk, Eggs, Cheese, Butter, Apples, Bananas, Cereal`

### 2. Analyze with Apriori (4 Marks)
- Converted the transaction list into one-hot encoded format using `pandas` and `TransactionEncoder` (mlxtend).
- Applied the **Apriori algorithm** with:
  - Minimum support = `0.3` (30%)

### 3. Generate Association Rules (3 Marks)
- Extracted rules from frequent itemsets using:
  - **Metric:** Confidence  
  - **Minimum confidence:** `0.7`
- Displayed at least 2 rules.

---

## 📘 Rule Explanation

### Example Rule:
> **If a customer buys Bread and Butter, they are also likely to buy Milk**  
> - Confidence: `0.80`

### 🧠 Real-Life Interpretation:
Customers who buy **Bread** and **Butter** also tend to buy **Milk**.  
This insight can help a store:
- Bundle Milk with Bread & Butter
- Optimize product placement (e.g., shelf layout)
- Create targeted promotions

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/halima-04/halima-association-mini
   cd halimam-association-mini
