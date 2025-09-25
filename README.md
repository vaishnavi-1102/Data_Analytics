# Task-1
# Netflix Titles Dataset

## Overview
This repository contains a cleaned and processed dataset of movies and TV shows available on Netflix. The dataset includes metadata such as titles, directors, cast, country of origin, dates added, release years, content ratings, durations, genres, and descriptions.

## Dataset Description
The dataset consists of the following columns:

| Column Name   | Description                                             |
| ------------- | ------------------------------------------------------- |
| show_id       | Unique identifier for each title                        |
| type          | Content type (Movie or TV Show)                         |
| title         | Title of the movie or TV show                           |
| director      | Director(s) of the title                                |
| cast          | Main cast members                                       |
| country       | Production countries                                    |
| date_added    | Date when the title was added to Netflix                |
| release_year  | Year the title was released                             |
| rating        | Content rating (e.g., PG-13, TV-MA)                     |
| duration      | Length of movie or number of seasons for TV shows      |
| listed_in     | Genres and categories assigned to the title            |
| description   | Brief synopsis or description of the content            |

## Data Cleaning Steps
- Imported raw data from CSV into Excel Power Query.
- Converted the `date_added` column to a proper date format.
- Trimmed whitespace and cleaned text columns using Power Query functions.
- Standardized text casing to lowercase where applicable.
- Removed duplicate and blank rows.
- Ensured correct data types for each column.
- Final cleaned dataset saved for analysis.

## Usage
This dataset can be used for:
- Analyzing content trends over time.
- Investigating distribution of content ratings.
- Exploring genre popularity.
- Building recommendation systems.
- Text analysis of descriptions or cast information.

## How to Use
1. Open the cleaned Excel file (e.g., `netflix_titles_cleaned.csv`).
2. Use Excel filtering, formulas, or visualization tools to analyze the data.
3. Alternatively, import the dataset into Python or other tools for machine learning or statistical analysis.

# Task-2
# Power BI Sales Analysis Dashboard

## Overview
This Power BI report provides a comprehensive sales and profit analysis using the Superstore dataset. It includes multiple visualizations to explore sales patterns across categories, regions, dates, products, and customer segments. The report aims to help stakeholders understand key business drivers and make data-driven decisions.

## Tools
- Power BI Desktop
- Data source: Superstore.csv

## Key Visuals & Insights

### Sum of Sales by Category
- Highlights sales performance across product categories.
- Technology leads sales, suggesting strong market preference.
- Most profit comes from select products, advising targeted marketing initiatives.
- The West region outperforms others in sales.

### Sum of Sales by Order Date
- Shows sales variation by order date to identify trends and seasonality.
- Helps forecast sales growth and plan inventory.

### Sum of Profit by Product Name
- Identifies most and least profitable products.
- Guides inventory and pricing strategies.

### Sum of Profit by Segment
- Displays profit distribution across consumer, corporate, and home office segments.
- Helps tailor marketing efforts to high-value customer groups.

### Sum of Sales by City
- Reveals urban markets driving sales.
- Supports resource allocation to key cities and growth in underperforming areas.

### Sum of Sales by Region
- Sales distribution across geographic regions.
- Highlights strong and weak markets for strategic focus.

### Sales by Shipping Mode
- Illustrates how sales are split among shipping options.
- Useful for optimizing shipping strategies and costs.

### Quantity Sold by Sub-Category
- Shows product popularity by quantity sold.
- Supports inventory management and product focus.

## How to Use
- Interact with slicers and filters to explore different facets of the business.
- Use the report to identify sales and profit drivers, customer preferences, and operational insights.
- Export the report as PDF or capture screenshots for presentations.

## Files
- `Superstore.csv`: Dataset used for analysis (no sensitive data).
- `SalesAnalysis.pbix`: Power BI report file with all visuals and measures.
- `README.md`: This documentation file.

## Recommendations
- Focus marketing on high performing categories and customer segments.
- Optimize inventory based on product quantity sold and profit.
- Improve shipping cost management by analyzing sales by shipping mode.
- Explore regional opportunities with tailored strategies.

# Task-3
# Sales Dashboard Project
# Objective
Create an interactive dashboard in Power BI that visualizes sales and operational KPIs for business stakeholders. The dashboard provides insights into product sales, agent performance, and customer activity.

# Dataset
Source: Product_Sales dataset (sample sales and call data)

Key fields: Agent_Name, ProductSold, Duration, CustomerID

Dashboard Components
KPI Cards
Sum of ProductSold: Total products sold across all agents.

Sum of Duration: Total operational duration (e.g., call duration).

# Visuals
Line Chart: Displays total products sold by each agent for performance comparison.

Slicer: Allows filtering by agent name to view agent-specific data.

# Features
Interactive slicers enable users to filter and drill into data by agent.

Clear visualization of sales volume and operational load.

Consistent color and layout for improved readability.

# Tools Used
Power BI Desktop for dashboard creation

Dataset imported from CSV/Excel format

# Outcome
This dashboard helps stakeholders monitor sales performance, optimize team efficiency, and make informed business decisions based on real-time data filters and visuals.



## Contact
For questions, feedback, or collaboration, please contact: [vadlakondavaishnavi2003@gmail.com]

---

*This README was generated to accompany the Netflix Titles dataset cleaning and analysis project.*
