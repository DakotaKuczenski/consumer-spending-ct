
Consumer Spending Analysis in Connecticut


--------------------------------------------------------------------------------

Overview

This project analyzes consumer spending trends in Connecticut from January 2020 to the present. Using publicly available data, we explore the impact of significant events like the COVID-19 lockdown, stimulus checks, and reopening phases. The goal is to uncover trends in consumer behavior, highlight economic resilience, and identify seasonal and category-specific insights.

--------------------------------------------------------------------------------

Key Questions

	Key Questions Answered

	1.	How has overall consumer spending changed over time?
	    We analyzed the general trend of consumer spending, highlighting major declines during the lockdown period and subsequent recovery.

        visuals/overall_spending.jpg


	2.	Which spending categories were most affected during the pandemic and recovery periods?
	    We compared pre-pandemic, lockdown, and post-reopening spending levels for categories like Grocery, Arts & Entertainment, and Accommodation & Food Services.

        visuals/trends_by_catagory.png


	3. What are the seasonal trends in spending across categories?
	    Identified cyclical patterns, such as holiday spending spikes in November-December and summer increases in travel-related categories.

        visuals/season_spending_trends.png

    4.	How resilient is Connecticut’s economy based on spending recovery patterns?
        We assessed post-reopening spending levels compared to pre-pandemic baselines to measure recovery and economic resilience.

        visuals/spending_recovery_catagory.png


--------------------------------------------------------------------------------

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

--------------------------------------------------------------------------------

Technologies Used

	•	Python: Data cleaning and analysis.
	•	Pandas: Data manipulation and aggregation.
	•	Matplotlib/Seaborn: Data visualization.
	•	Jupyter Notebook: Documentation and analysis workflow.


--------------------------------------------------------------------------------

Methodology

	1.	Data Preparation:
	    •Cleaned and transformed raw data into a structured format for analysis.
	    •Renamed columns and converted date formats for consistency.
	2.	Event Annotations:
	    •Added significant events like Lockdown Starts, Stimulus Checks, and Reopening Begins for contextual insights.
	3.	Exploratory Data Analysis (EDA):
	    •Analyzed overall and category-specific spending patterns.
	    •Compared spending levels during Pre-Pandemic, Lockdown, and Post-Reopening periods.
	4.	Visualizations:
	    •Created time-series plots, bar charts, and seasonal trend graphs to communicate findings.


--------------------------------------------------------------------------------

Findings

1. Overall Spending Trends

	•	Insight: Consumer spending declined significantly during lockdowns but showed steady recovery post-reopening.
	•	Graph: Overall Spending Trend

2. Category-Specific Insights

	•	Grocery Spending:
	•	Increased by ~19% during lockdowns due to stockpiling and at-home cooking.
	•	Arts & Entertainment:
	•	Declined by ~37% during lockdowns and experienced the slowest recovery post-reopening.
	•	Accommodation & Food Services:
	•	Dropped by ~27% during lockdowns but recovered to a ~12% increase post-reopening.
	•	Graph: Category-Specific Trends

3. Seasonal Patterns

	•	Spending spikes in November-December indicate strong holiday shopping behavior.
	•	Summer months show recovery in travel-related spending.
	•	Graph: Seasonal Trends

4. Economic Resilience

	•	Grocery spending exceeded pre-pandemic levels consistently.
	•	Non-essential categories like Arts & Entertainment remain below pre-pandemic levels.
	•	Graph: Spending Recovery Comparison


--------------------------------------------------------------------------------

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
│   
├── README.md             
│
├── requirements.txt    


--------------------------------------------------------------------------------

Next Steps

	1.	Extend the analysis to other states or regions for a comparative study.
	2.	Incorporate predictive modeling to forecast spending trends.
	3.	Build an interactive dashboard for dynamic exploration.

--------------------------------------------------------------------------------

Acknowledgements

Special thanks to data.gov for providing the dataset used in this analysis.