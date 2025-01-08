# Customer Segmentation using KMeans Clustering

This project demonstrates the use of the **KMeans Clustering** algorithm to perform customer segmentation based on a mall customers dataset (`mall_customers.csv`). The goal is to group customers into distinct segments based on their spending habits and income levels, enabling better targeted marketing strategies.

## Dataset

The dataset, `mall_customers.csv`, contains information about customers, including:
- **CustomerID**: Unique ID for each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: Score assigned by the mall based on customer spending behavior.

## Key Steps in the Project

1. **Data Preprocessing**:
   - Handling missing values (if any).
   - Encoding categorical data (Gender).
   - Feature scaling for optimal clustering.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizing the distribution of customer demographics.
   - Analyzing spending patterns and income levels.

3. **Optimal Cluster Identification**:
   - Using the **Elbow Method** to determine the optimal number of clusters.

4. **Model Training**:
   - Applying the **KMeans Clustering** algorithm to segment customers.

5. **Visualization**:
   - Visualizing the clusters with respect to various features such as:
     - Income vs. Spending Score
     - Age vs. Spending Score

## Technologies Used

- **Python** for implementation
- Libraries:
  - `pandas` for data manipulation
  - `numpy` for numerical operations
  - `matplotlib` and `seaborn` for data visualization
  - `sklearn` for implementing the KMeans clustering algorithm

## Project Structure

```plaintext
├── mall_customers.csv    # Dataset
├── kmeans_clustering.ipynb  # Jupyter Notebook with code and analysis
├── requirement.txt
├── README.md             # Project description
```

How to Run the Project
1. Clone the repository: bash git clone https://github.com/teamarnab/customer-segmentation-kmeans-project
2. Install the required libraries: bash install pandas numpy matplotlib seaborn scikit-learn
3. Open the kmeans_clustering.ipynb notebook in Jupyter or VSCode.
4. Run the notebook step-by-step to view the analysis and results.

Results
The KMeans clustering algorithm successfully segmented customers into groups based on their spending scores and income levels, providing insights for targeted marketing strategies.

Future Improvements
Incorporate additional features such as customer transaction history.
Experiment with other clustering algorithms like Hierarchical Clustering or DBSCAN.
Automate customer segmentation using a web application or dashboard.
