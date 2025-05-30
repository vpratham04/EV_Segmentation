# EV_Segmentation
EV Market Segmentation Analysis for Indian Startup
Introduction
This project conducts a detailed market segmentation analysis for the Electric Vehicle (EV) market in India, utilizing customer demographics, vehicle sales data, and ownership patterns across states and economic classes. The goal is to deliver actionable insights for an Indian startup aiming to penetrate the EV market.
Objectives
The main objectives of this analysis are to:

Identify key customer segments based on demographic and economic factors.
Determine the most promising EV type for the Indian market.
Provide data-driven recommendations for market entry and product positioning.

Datasets
The analysis leverages the following datasets:

age_income.csv: Customer demographic data, including age, income, and other attributes (20,000 rows, 27 columns).
Sales of motor vehicles of India.csv: Vehicle sales data across various categories in India (12 rows, 10 columns).
Share of households owning cars and two-wheelers by state (2023) - Data For India.csv: State-wise ownership data for cars and two-wheelers (36 rows, 4 columns).
Vehicle Class - All.csv: Information on vehicle classes and their registrations (16 rows, 2 columns).
Vehicle ownership by economic class - Data For India.csv: Vehicle ownership patterns across economic classes (10 rows, 5 columns).

Methodology
The analysis follows these key steps:

Data Loading and Preprocessing: Importing and cleaning datasets for quality and consistency.
Exploratory Data Analysis (EDA): Initial analysis to uncover data distributions and relationships.
Customer Segmentation: Applying K-means clustering to segment customers based on demographic and economic factors.
Vehicle Sales and Ownership Analysis: Examining sales and ownership data to identify market trends.
Target Segment and Vehicle Type Identification: Using clustering and market analysis to select target segments and EV types.
Visualization: Generating visualizations (e.g., pie charts, scatter plots, bar charts) to illustrate findings.

Key Findings and Recommendations

Market Opportunity: Two-wheelers dominate with a 73.3% market share, highlighting a strong potential for electric two-wheelers.
Target Vehicle: Electric scooters are recommended due to their mass market appeal and alignment with ownership trends.
Primary Target Segment: Young urban professionals (25-35 years) in Tier-1 cities, representing 2,496 potential customers.
Secondary Target Segment: Middle-income families in Tier-2 cities, offering expansion opportunities.
Geographic Focus: Initial focus on top metro cities, with subsequent expansion to Tier-2 cities.
Market Size: The primary segment provides a substantial market, with growth potential across additional segments.

Technologies and Libraries
The project is implemented in Python with the following libraries:

Pandas: Data manipulation and analysis.
NumPy: Numerical computations.
Matplotlib: Visualization creation.
Seaborn: Enhanced data visualization.
Scikit-learn: Machine learning (K-means clustering, PCA, etc.).

Acknowledgments
The datasets are sourced from publicly available data for India. Proper citations and acknowledgments should be included when using this analysis for research or commercial purposes.

This README provides an overview of the EV Market Segmentation Analysis project. For detailed implementation, refer to the EV_segmentation.ipynb notebook.
