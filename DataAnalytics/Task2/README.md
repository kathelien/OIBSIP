# Task 2: Customer Segmentation Analysis

## Oasis Infobyte Internship

### Project Overview
This project focuses on segmenting e-commerce customers based on their purchasing behaviour using RFM analysis and the K-Means clustering algorithm. The objective is to identify different customer groups and recommend suitable marketing strategies for each segment.

### Objective
To analyse customer purchasing patterns, group customers into meaningful segments, and support targeted marketing decisions.

### Dataset
- **Dataset:** Online Retail Customer Transaction Dataset
- **Format:** Excel
- **Rows and columns before cleaning:** 525,461 rows and 8 columns
- **Main features:** Invoice, StockCode, Description, Quantity, InvoiceDate, Price, Customer ID, and Country

### Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab
- Excel

### Project Methodology
1. Loaded and inspected the dataset.
2. Cleaned missing and invalid data.
3. Removed cancelled invoices and non-positive quantities or prices.
4. Calculated customer-level RFM metrics:
   - **Recency:** Days since the customer's latest purchase.
   - **Frequency:** Number of unique invoices per customer.
   - **Monetary:** Total customer spending.
5. Standardised the RFM features using StandardScaler.
6. Used the Elbow Method to help select the number of clusters.
7. Applied K-Means clustering to segment customers.
8. Visualised customer clusters using scatter plots.
9. Analysed cluster profiles and customer counts.
10. Developed marketing recommendations for customer segments.

### Visualisations
- Elbow Method graph
- Frequency vs Monetary scatter plot
- Recency vs Monetary scatter plot
- Customer count by cluster bar chart

### Customer Segmentation Insights
The cluster profiles are used to compare customer recency, purchase frequency, and spending. Based on the observed patterns, possible marketing strategies include loyalty rewards, personalised discounts, win-back campaigns, cross-selling, and product recommendations.

*Final segment labels and marketing recommendations should be interpreted using the actual cluster profile results.*

### Key Learning Outcomes
- Data cleaning and exploratory analysis
- RFM customer analysis
- Feature standardisation
- K-Means clustering
- Data visualisation
- Customer profiling and marketing insights

### Project Deliverables
- Jupyter Notebook (`.ipynb`)
- PDF report
- Customer segmentation results (CSV)
- Cluster profile results (CSV)
- Project screenshots
- Demo video

### Conclusion
This project demonstrates how customer transaction data can be analysed using RFM metrics and K-Means clustering to identify customer groups and develop data-driven marketing recommendations.

### Internship
Oasis Infobyte Internship — Task 2: Customer Segmentation Analysis
