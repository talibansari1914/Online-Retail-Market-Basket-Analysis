# 🛒 Market Basket Analysis using Apriori Algorithm

## 📌 Project Overview
This project performs **Market Basket Analysis** on retail transaction data to discover frequently co-purchased products using the Apriori algorithm.<br>

The objective is to uncover hidden purchasing patterns that can help businesses improve:<br>
- Cross-selling strategies<br>
- Product bundling<br>
- Recommendation systems<br>
- Inventory planning<br>

---

## 📂 Dataset
The dataset contains retail transaction records including:<br>
- Invoice Number<br>
- Product Description<br>
- Quantity<br>
- Unit Price<br>
- Customer ID<br>
- Country<br>

Each row represents a product purchased in a transaction.<br>

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:<br>

- Removed cancelled invoices<br>
- Removed negative quantities (returns)<br>
- Handled missing values<br>
- Converted numeric variables (Quantity, UnitPrice) into categorical bins<br>
- Grouped transactions by InvoiceNo<br>
- Converted transactions into one-hot encoded format using `TransactionEncoder`<br>

---

## 🔎 Methodology

### 1️⃣ Frequent Itemset Generation<br>
The **Apriori algorithm** was applied to extract frequent itemsets based on minimum support threshold.<br>

### 2️⃣ Association Rule Mining
Association rules were generated using:<br>
- **Support**<br>
- **Confidence**<br>
- **Lift**<br>

Rules with Lift > 1 were considered meaningful.<br>

---

## 📊 Visualizations

The project includes:<br>

- Top 10 Most Frequent Products<br>
- Support vs Confidence Scatter Plot<br>
- Top Association Rules by Lift<br>

These visualizations help interpret the strength and quality of associations.<br>

---

## 💡 Key Insights

- Certain products are frequently purchased together.<br>
- High lift values indicate strong product associations.<br>
- High confidence rules suggest predictable customer behavior.<br>
- Results can support bundling and recommendation strategies.<br>

---

## 🛠️ Technologies Used

- Python<br>
- Pandas<br>
- Matplotlib<br>
- Seaborn<br>
- mlxtend (Apriori & Association Rules)<br>

---

## 🚀 How to Run

1. Clone the repository<br>
2. Install required libraries:<br>
   ```bash<br>
   pip install pandas numpy matplotlib seaborn mlxtend<br>
3.Run the Jupyter Notebook:<br>
 jupyter notebook Online_Retail.ipynb<br>

 ---
 
 ## Business Impact

1.Market Basket Analysis helps businesses:<br>
2.Increase average basket value<br>
3.Improve product placement<br>
4.Design targeted promotions<br>
5.Enhance recommendation systems<br>

---

## 🧠 Conclusion

1.This project successfully demonstrates how association rule mining can extract meaningful insights from retail transaction data.<br>
2.The Apriori algorithm effectively identifies strong item relationships that can drive data-informed business decisions.<br>

## 📌 Author:
**Abbu Talib Ansari**<br>
*GitHub:https://github.com/talibansari1914*

