# Zeotap Data Science Assignment

This repository contains the solution for an eCommerce transactions dataset assignment. It is organized into three main tasks:

1. **Exploratory Data Analysis (EDA) and Business Insights**  
   - Jupyter notebook for EDA: `ANIL_JHA_EDA.ipynb`  
   - PDF report with at least 5 business insights: `ANIL_JHA_EDA.pdf`

2. **Lookalike Model**  
   - Jupyter notebook that builds a model to recommend 3 similar customers: `ANIL_JHA_Lookalike.ipynb`  
   - A CSV file listing top 3 lookalikes (with similarity scores) for customers C0001 to C0020: `ANIL_JHA_Lookalike.csv`

3. **Customer Segmentation / Clustering**  
   - Jupyter notebook demonstrating clustering on the customer data: `ANIL_JHA_Clustering.ipynb`  
   - PDF report with the number of clusters, DB Index, and visualizations: `ANIL_JHA_Clustering.pdf`

## Repository Structure
.
├── FirstName_LastName_EDA.ipynb
├── FirstName_LastName_EDA.pdf
├── FirstName_LastName_Lookalike.ipynb
├── FirstName_LastName_Lookalike.csv
├── FirstName_LastName_Clustering.ipynb
├── FirstName_LastName_Clustering.pdf
├── data/
│ ├── Customers.csv
│ ├── Products.csv
│ └── Transactions.csv
└── README.md


- *data/* folder contains the three CSV files:
  - **Customers.csv**  
  - **Products.csv**  
  - **Transactions.csv**  

## Running the Notebooks

1. **Set up a virtual environment** (optional but recommended)  
python -m venv venv
source venv/bin/activate # or venv\Scripts\activate on Windows

2. **Install required libraries**  
Make sure you have the standard data science libraries (pandas, numpy, matplotlib, seaborn, scikit-learn, etc.).

3. **Open the notebooks**  
- Run `ANIL_JHA_EDA.ipynb` to replicate the exploratory data analysis and generate insights.  
- Run `ANIL_JHA_Lookalike.ipynb` to see the lookalike model in action and produce `ANIL_JHA_Lookalike.csv`.  
- Run `ANIL_JHA_Clustering.ipynb` to perform customer segmentation and evaluate clustering metrics.

## Highlights

- **EDA**: Uncover key patterns in spending behavior, regional distribution, top-selling products, and more.  
- **Lookalike Model**:  
- Uses engineered features (RFM, days since signup, etc.).  
- Employs cosine similarity on standardized features to identify the top 3 similar customers for each requested user.  
- Produces a CSV mapping each of the first 20 customers to their most similar counterparts.  
- **Clustering**:  
- Demonstrates how customers can be segmented based on transaction volume, frequency, recency, product category preferences, etc.  
- Includes the Davies-Bouldin Index to measure cluster quality.  
- Provides visual representations of clusters via dimensionality reduction.

Happy Coding!




