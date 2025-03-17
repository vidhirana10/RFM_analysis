# RFM Analysis

## Overview
This project performs **RFM (Recency, Frequency, Monetary) Analysis** on customer transaction data to segment customers based on their purchasing behavior. RFM analysis is a marketing technique used to identify high-value customers and improve customer retention strategies.

By analyzing past transaction data, businesses can gain valuable insights into customer engagement, spending habits, and loyalty. This information helps in designing targeted marketing campaigns and improving customer relationship management.

## Features
- **Data Cleaning & Preprocessing**: Handles missing values, duplicates, and formats data for analysis.
- **RFM Score Calculation**: Computes Recency, Frequency, and Monetary scores for each customer.
- **Customer Segmentation**: Segments customers based on their RFM scores into various groups such as high-value customers, at-risk customers, and inactive users.
- **Visualization & Insights**: Provides charts, tables, and statistical summaries for easy interpretation of results.
- **Customizable Thresholds**: Allows users to modify the segmentation criteria based on business needs.
- **Exportable Reports**: Generates summary reports that can be exported for further business analysis.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Required Python libraries (see below)

### Clone the Repository
To get started with this project, clone the repository from GitHub:
```bash
git clone https://github.com/vidhirana10/RFM_analysis.git
cd RFM_analysis
```

### Install Dependencies
Install the required dependencies using the following command:
```bash
pip install -r requirements.txt
```

## Usage
### Running the Analysis
1. Open Jupyter Notebook:
```bash
jupyter notebook
```
2. Navigate to `main.ipynb` and execute the notebook step by step.
3. The script will preprocess the data, calculate RFM scores, and segment customers.
4. Visualizations and insights will be displayed at the end of the notebook.

### Understanding the Dataset
The dataset should contain transaction records with at least the following columns:
  - **Customer ID**: Unique identifier for each customer.
  - **Transaction Date**: Date of the transaction.
  - **Transaction Amount**: Value of the transaction.

This dataset allows us to evaluate customer engagement and purchasing behavior effectively.

## RFM Calculation
- **Recency (R)**: Measures how recently a customer has made a purchase. Customers with the most recent transactions receive higher scores.
- **Frequency (F)**: Counts how many times a customer has purchased within a specific timeframe. Higher frequency leads to higher scores.
- **Monetary (M)**: Represents the total amount spent by a customer. Higher spending results in higher scores.

### Segmentation Strategy
Based on RFM scores, customers are grouped into different segments, such as:
- **Best Customers**: High recency, high frequency, high monetary.
- **Loyal Customers**: High frequency, moderate recency.
- **At Risk Customers**: Low recency, moderate frequency, moderate monetary.
- **Churned Customers**: Low recency, low frequency, low monetary.

Each segment can be targeted differently to improve engagement and retention.

## Results & Visualization
The analysis provides:
- **Distribution of RFM scores**: Helps understand the spread of customer behavior.
- **Heatmaps & Scatter Plots**: Visualizes customer segmentation.
- **Customer Grouping Insights**: Identifies potential strategies for improving engagement.

### Example Visualizations
- **RFM Score Distribution**: Shows how scores are spread across customers.
- **Customer Segmentation Heatmap**: Displays customer groupings based on RFM values.
- **Monetary vs. Frequency Scatter Plot**: Identifies high-value customers who frequently purchase.

## Benefits of RFM Analysis
- Helps in designing **targeted marketing campaigns**.
- Improves **customer retention** strategies.
- Increases **customer lifetime value (CLV)** by identifying high-value customers.
- Provides actionable insights for **personalized promotions and discounts**.

## Customization & Extensibility
The analysis can be customized by modifying:
- The thresholds used for segmenting customers.
- The dataset to include additional customer attributes.
- The visualization techniques to better suit specific business needs.

## Contributing
If you would like to contribute:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request for review.

## License
This project is licensed under the MIT License.

## Contact
For any questions, suggestions, or collaboration opportunities, feel free to reach out to **vidhirana10** on GitHub.

---

Happy Analyzing! 🚀

