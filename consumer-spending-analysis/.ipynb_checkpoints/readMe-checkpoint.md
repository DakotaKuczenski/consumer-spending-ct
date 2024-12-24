
Analyzing Consumer Spending Trends During COVID-19 and After


Overview

This project explores changes in consumer spending patterns across various categories in Connecticut from January 2020 onward. Using publicly available data, the analysis uncovers the economic impact of key events like the COVID-19 pandemic, recovery phases, and inflation on consumer behavior.

Key Questions

	1.	How has overall consumer spending changed over time?
	2.	Which spending categories were most affected during the pandemic and recovery periods?
	3.	What are the seasonal trends in spending across categories?
	4.	Are there correlations between spending patterns in different categories (e.g., grocery vs. dining)?
	5.	How resilient is Connecticut’s economy based on its spending recovery patterns?

Dataset

	•	Source: data.gov -> https://catalog.data.gov/dataset/percent-change-in-consumer-spending-january-2020-through-the-present
    
	•	Description:
	•	Time series data on percent changes in consumer spending across various categories.
	•	Covers Connecticut only, broken down by:
	•	Accommodation and Food Service (ACF)
	•	Arts, Entertainment, and Recreation (AER)
	•	General Merchandise Stores and Apparel (GEN, AAP)
	•	Grocery and Food Stores (GRF)
	•	Transportation and Warehousing (TWS)
	•	Retail Spending (with and without groceries)

Technologies Used

	•	Python: Data cleaning and analysis.
	•	Pandas: Data manipulation and aggregation.
	•	Matplotlib/Seaborn: Data visualization.
	•	Jupyter Notebook: Documentation and analysis workflow.

Project Structure

consumer-spending-analysis/
│
├── data/
│   ├── Percent_Change_in_Consumer_Spending.csv  # Raw dataset
│
├── notebooks/
│   ├── consumer_spending_analysis.ipynb  # Jupyter notebook with analysis
│
├── visuals/
│   ├── overall_trend.png               # Visualization: Overall trends
│   ├── category_comparison.png         # Visualization: Spending by category
│
├── README.md             
│
├── requirements.txt    




