# Smart Supermarket

A professional, interactive shopping web app with built-in data mining analytics. This project simulates a modern supermarket experience and demonstrates clustering and association rule mining on shopping cart data.

## Features
- **Modern Shopping UI:** Add/remove products to your cart, view transaction history, and clear transactions.
- **Sample Data Generation:** Instantly populate the app with realistic sample transactions.
- **Data Mining Analysis:**
  - **K-Means Clustering:** Groups similar transactions to identify customer segments.
  - **Association Rules (Apriori):** Finds which products are frequently bought together.
- **Responsive Design:** Looks great on desktop and mobile.

## How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/catacisneros/Supermarket.git
   cd Supermarket
   ```
2. **Open `index.html` in your browser.**
   - No server or build step required—just open the file!

## Technologies Used
- **HTML5 & CSS3** (with Google Fonts for a modern look)
- **Vanilla JavaScript** (no frameworks)
- **Data Mining Algorithms:** Custom implementations of K-Means and Apriori

## Data Mining Explanation
- **K-Means Clustering:**
  - Groups transactions into clusters based on items bought together.
  - Helps identify different types of shoppers or common purchase patterns.
- **Association Rules (Apriori):**
  - Finds rules like "If a customer buys Milk and Eggs, they often buy Cheese."
  - Shows support, confidence, and lift for each rule.

## Demo Use Cases
- Simulate shopping by selecting products and completing transactions.
- Generate sample data for instant analysis.
- Click "Analyze Data" to see customer segments and product associations.

---

**This project is a prototype for educational and demonstration purposes.** 