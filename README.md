# Excel Sales Analysis with Pivot Tables

This project demonstrates how to analyze sales data in **Microsoft Excel** using **Pivot Tables** and **Pivot Charts**.

---

## 📂 Dataset Structure
Make sure your dataset has at least the following columns:

- **OrderID** – Unique order identifier  
- **Branch** – Branch name (e.g., Chennai, Bangalore, Delhi)  
- **Product** – Product category (e.g., Mobile, Laptop, Accessories)  
- **Gender** – Customer gender (Male/Female)  
- **SalesAmount** – Sales value  
- **Date** – Order date  

Example row:

| OrderID | Branch   | Product      | Gender | SalesAmount | Date       |
|---------|----------|--------------|--------|-------------|------------|
| 1001    | Chennai  | Mobile       | Male   | 25000       | 2025-01-15 |

---

## 📊 Step-by-Step Implementation

### 1. Load Data into Excel
1. Open **Excel**.  
2. Paste or import the dataset into a new sheet.  
3. Ensure the columns are formatted properly (Date as Date, SalesAmount as Number).  

---

### 2. Create Pivot Table
1. Select the dataset range.  
2. Go to **Insert → Pivot Table**.  
3. Choose **New Worksheet** and click **OK**.  

---

### 3. Branch-wise Sales
- Drag **Branch** → Rows  
- Drag **SalesAmount** → Values  
- Result: Shows total sales per branch.  

---

### 4. Product-wise Sales
- Drag **Product** → Rows  
- Drag **SalesAmount** → Values  
- Result: Sales distribution by product category.  

---

### 5. Gender-wise Sales
- Drag **Gender** → Rows  
- Drag **SalesAmount** → Value
