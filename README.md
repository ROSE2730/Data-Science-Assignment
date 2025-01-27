





# **Data Science Intern Assignment**

This repository contains the solutions for the **Data Science Intern Assignment**. The assignment focuses on analyzing eCommerce transactions and involves three key tasks: **Exploratory Data Analysis (EDA)**, **Lookalike Model**, and **Customer Segmentation/Clustering**.

---

## **Repository Structure**

```
├── Customers.csv                # Customer dataset
├── Products.csv                 # Product dataset
├── Transactions.csv             # Transactions dataset
├── FirstName_LastName_EDA.ipynb # EDA code
├── FirstName_LastName_EDA.pdf   # EDA insights report
├── FirstName_LastName_Lookalike.ipynb # Lookalike model code
├── FirstName_LastName_Lookalike.csv   # Lookalike model output
├── FirstName_LastName_Clustering.ipynb # Clustering code
├── FirstName_LastName_Clustering.pdf   # Clustering results report
└── README.md                    # Readme file for the repository
```

---

## **Tasks**

### **1. Task 1: Exploratory Data Analysis (EDA)**
- **Objective**: Analyze the provided datasets to derive insights and summarize findings.
- **Deliverables**:
  - A Python/Jupyter Notebook (`EDA.ipynb`) with code for data analysis.
  - A PDF report summarizing business insights.

---

### **2. Task 2: Lookalike Model**
- **Objective**: Build a model to recommend 3 similar customers for the first 20 customers based on profile and transaction history.
- **Deliverables**:
  - A Python/Jupyter Notebook (`Lookalike.ipynb`) with the model development.
  - An output CSV file (`Lookalike.csv`) with top 3 recommendations for each customer.

---

### **3. Task 3: Customer Segmentation/Clustering**
- **Objective**: Perform customer segmentation using clustering techniques.
- **Deliverables**:
  - A Python/Jupyter Notebook (`Clustering.ipynb`) with clustering code.
  - A PDF report summarizing:
    - Number of clusters formed.
    - Davies-Bouldin (DB) Index value.
    - Visualizations and additional metrics.

---

## **Datasets**

### 1. `Customers.csv`
- Contains customer profile information:
  - **CustomerID**: Unique customer identifier.
  - **CustomerName**: Name of the customer.
  - **Region**: Customer's region.
  - **SignupDate**: Date when the customer signed up.

### 2. `Products.csv`
- Contains product information:
  - **ProductID**: Unique product identifier.
  - **ProductName**: Name of the product.
  - **Category**: Product category.
  - **Price**: Product price in USD.

### 3. `Transactions.csv`
- Contains transaction details:
  - **TransactionID**: Unique identifier for each transaction.
  - **CustomerID**: Customer ID linked to the transaction.
  - **ProductID**: Product ID linked to the transaction.
  - **TransactionDate**: Date of the transaction.
  - **Quantity**: Number of products purchased.
  - **TotalValue**: Total transaction value.
  - **Price**: Price of the product sold.

---

## **How to Run**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YourGitHubUsername/Assignment-DataScience-Intern.git
   cd Assignment-DataScience-Intern
   ```

2. **Install Dependencies**:
   Make sure you have Python 3.x and the required libraries installed. Use the following command to install the dependencies:
   ```bash
   pip install -r requirements.txt

   ```

3. **Run the Notebooks**:
   - Open each notebook (`EDA.ipynb`, `Lookalike.ipynb`, `Clustering.ipynb`) in Jupyter Notebook or Jupyter Lab.
   - Run the cells sequentially to execute the code.

4. **Generated Outputs**:
   - The outputs (`Lookalike.csv`, clustering visualizations) will be saved in the current directory.

---

## **Results and Insights**

- **EDA**:
  - Derives business insights on customer behavior, product popularity, and revenue trends.
- **Lookalike Model**:
  - Provides customer recommendations based on similarity scores.
- **Clustering**:
  - Segments customers into distinct groups for targeted strategies.

---

