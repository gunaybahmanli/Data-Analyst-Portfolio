# Gunay Bahmanli-Data Analyst Portfolio
# [Project 1: SQL | POWER BI Travel Insights Dashboard] (https://github.com/gunaybahmanli/Travel-Insights-Dashboard)

This Travel Insights Dashboard leverages SQL for data preparation and Power BI for dynamic visualizations, offering a clear and interactive view of key travel trends, costs, and traveler behaviors, providing valuable insights for data-driven decision-making.

The visualizations were split between two pages to offer both a high-level overview and detailed insights.

Project Overview: Travel Insights Dashboard
This project utilizes a dataset containing detailed travel information, including destination, traveler demographics, trip duration, and costs. The dashboard was developed using SQL for data cleaning, transformation, and querying, while Power BI was employed for creating interactive and insightful visualizations. This combination allows for a deeper understanding of travel patterns, cost analysis, and traveler demographics, making the dashboard an essential tool for analyzing global travel trends.

Breakdown of the key queries executed in SQL and the corresponding insights they provide:

Splitting Destination (City and Country):

Query: I split the Destination column into City and Country for more granular analysis.
Purpose: Allows detailed insights into travel patterns by both city and country, improving the clarity of visualizations in Power BI.

Total Number of Trips per Destination:

Query: Counts the number of trips per City and Country after splitting the destination.
Purpose: Helps identify the most popular destinations globally.
Visualization: Map and bar chart in Power BI to visually depict trip volumes for different destinations.

Average Accommodation and Transportation Cost per Destination:

Query: Calculates the average accommodation and transportation costs per city and country.
Purpose: Highlights the most expensive or affordable travel destinations based on costs.
Visualization: Bar chart to compare costs per destination and help users quickly assess travel expenses.

Most Commonly Used Transportation Types:

Query: Retrieves the count and average cost for each Transportation_type.
Purpose: Provides insight into preferred travel methods and their cost implications.
Visualization: Pie chart displaying the distribution of transportation methods, with a bar chart comparing average costs per method.

Demographic Breakdown of Travelers:

Query: Analyzes the demographics of travelers, including Traveler_gender, Traveler_nationality, and Traveler_age.
Purpose: Offers insights into the types of travelers (e.g., gender, age, nationality) and their trip preferences.
Visualization: Stacked bar chart displaying the demographic distribution, providing a clear view of traveler profiles.

Average Trip Duration per Destination:

Query: Calculates the average duration of trips to each destination.
Purpose: Helps identify whether certain destinations tend to involve longer or shorter stays.
Visualization: Line chart showing the average trip length for each destination.

Total Cost of Trips per Traveler:

Query: Sums the accommodation and transportation costs per traveler to determine the total amount spent.
Purpose: Reveals spending patterns of individual travelers, identifying high-spending or frequent travelers.
Visualization: Table/matrix that lists total spending per traveler, offering detailed insights into individual travel expenses.
