# Market_basket_analysis-uding-ECLAT
# Market Basket Analysis Using ECLAT

This repository demonstrates how to perform **Market Basket Analysis** using the **ECLAT (Equivalence Class Clustering and bottom-up Lattice Traversal)** algorithm to find frequent itemsets in transactional datasets.

## 🧠 Project Overview

Market Basket Analysis is a common data mining technique used to discover associations between products or items in transaction datasets. Rather than scanning pairs like Apriori, the **ECLAT** algorithm uses a **vertical data format** and intersection operations to efficiently find frequent itemsets based on support.

This project contains a Jupyter Notebook that:
- Loads and preprocesses transactional data
- Applies the ECLAT algorithm to find frequent itemsets
- Enables further exploration of patterns in purchase behavior

## 📁 Repository Contents

- `Market_basket_analysis_uding_ECLAT.ipynb` — The main notebook showing ECLAT implementation and results.

## 📦 Dependencies

Make sure you have the following Python packages installed:

```bash
pip install pandas mlxtend jupyter
(You can list additional packages if required by the notebook.)

🚀 How to Run
Clone this repository:

bash
Copy code
git clone https://github.com/DhanushN2005/Market_basket_analysis-uding-ECLAT.git
Navigate into the project folder:

bash
Copy code
cd Market_basket_analysis-uding-ECLAT
Open the notebook:

bash
Copy code
jupyter notebook Market_basket_analysis_uding_ECLAT.ipynb
