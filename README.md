Seattle Housing Data Analysis

****

Overview

This project is designed for a family looking to buy a home in the Seattle area. Their goal is to stay as close to Seattle as possible while finding the best value—specifically, obtaining the most square footage for the best price. Using a large dataset of property sales records from Washington State, this analysis evaluates property prices, quality, and square footage to identify optimal cities and neighborhoods.

****

Scenario & Objectives

Scenario: A family is searching for a house near Seattle. They want to balance proximity to the city with value—maximizing square footage at a reasonable price.
Objectives:
Identify which cities have the highest median property prices.
Determine the cities with the highest quality homes (filtered by 5-star ratings).
Find out which cities offer the most square footage.
Analyze the median cost per square foot across top cities.
Map these findings to assess proximity to Seattle and pinpoint promising areas (e.g., Mercer Island).

****

Data Overview

The dataset comprises property sales records across Washington state. Key points include:

Unknown Format & Data Quality: Data required extensive cleaning due to unknown format and quality issues.
Indicators of Market Health: Property prices, square footage, and quality ratings serve as indicators of both market conditions and economic health.
Key Metrics Analyzed:
Median property prices per city.
Home quality ratings.
Median square footage.
Cost per square foot.

****

Methodology

Data Cleaning (Python):
Used Python scripts to load, inspect, and clean the raw dataset.
Addressed missing values, data type inconsistencies, and other quality issues.
Basic Analysis (SQL):
Employed SQL queries to extract summary statistics and aggregate key metrics by city.
Generated preliminary insights on median prices, square footage, and other relevant factors.
Visualization & In-Depth Analysis (Tableau):
Created interactive dashboards to visualize:
The top 10 cities with the highest median home prices.
Cities with the highest quality homes (filtered to 5-star ratings).
The top 10 cities with the largest median square footage.
Median cost per square foot across the top 20 cities.
A geographic map plotting cities in relation to Seattle and highlighting their median home prices.
These visualizations allowed for an in-depth comparison, revealing that while cities like Medina, Yarrow Point, and Clyde Hill have high prices and large square footage, Mercer Island offers a compelling balance between proximity to Seattle, adequate square footage, and a more affordable median cost.


****

Key Findings

Most Expensive Cities:
The top 10 cities with the highest median home prices include Medina, Yarrow Point, and Clyde Hill. While these areas offer spacious homes, they might be overpriced for some buyers.
Quality Homes:
Cities with 5-star rated homes largely overlap with the most expensive markets. Investing in these areas could mean higher quality properties with potentially lower maintenance costs.
Square Footage:
Analysis shows that cities like Medina and Yarrow Point lead in median square footage. Mercer Island also appears on this list, yet it has a significantly lower median cost than the top expensive cities.
Cost per Square Foot:
Although Medina, Yarrow Point, and Clyde Hill rank high in median cost per square foot, Mercer Island (and to some extent Bellevue) offer larger homes at more competitive rates.
Proximity to Seattle:
When mapping the data, Bellevue was found to be less ideal due to its distance from Seattle. In contrast, Mercer Island is very close to Seattle, offering a favorable balance of space and price.
****

Conclusion & Recommendations

Based on the analysis:

Mercer Island emerges as a strong candidate for the family, as it provides a reasonable median cost, ample square footage, and excellent proximity to Seattle.
While other cities offer luxurious or high-quality homes, the price-to-space ratio combined with location makes Mercer Island a compelling option for long-term investment.

****
Tools & Technologies

Python: For data cleaning and preprocessing.
SQL: For querying and summarizing data.
Tableau: For creating interactive dashboards and visualizations.

****

How to Run the Project

Data Cleaning:
Run the Python scripts in your preferred IDE or Jupyter Notebook.
SQL Analysis:
Use your SQL client to execute the provided queries against the cleaned dataset.
Visualization:
Open the Tableau workbook to explore the dashboards.
****

Future Work

Incorporate additional datasets (e.g., neighborhood amenities, school ratings) for more comprehensive insights.
Refine machine learning models to predict future property price trends based on historical data.
