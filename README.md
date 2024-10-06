# BSC-Budget-Plan

📚 About Data

The dataset includes details on call centers, their sales performance across different regions, categories, and subcategories. It provides metrics on order count, customer count, revenue, profit, and forecasts for revenue and profit. 

  - Regions Covered: Southeast (based on the sample)
  - Categories: Books, with subcategories like Art & Architecture, Business, Literature, and more.
  - Metrics: Sales performance measures such as units sold, revenue, and profit forecasts.

💡 Highlights

  - Revenue Performance: Subcategories like "Books - Business" showed high revenue with 226 units sold and a profit margin of over 54%.
  - Customer Trends: The "Literature" subcategory had the highest customer count in the sample with 19 customers, leading to a substantial number of units sold (27 units).
  - Revenue and Profit Forecasts: Across categories, revenue and profit forecasts vary, with some categories like "Science & Technology" showing forecasted revenue that exceeds actual sales (e.g., $213.06 forecast vs. $201 actual).

✏️ Data Wrangling

Conducted data wrangling and cleaning to ensure the integrity of the dataset for the analysis of historical sales data and budget forecasting:

  - Removed rows with missing values: Ensured all records with incomplete data, especially in critical columns like revenue, were removed.
  - Standardized Region and Category names: Corrected any inconsistencies in region names (e.g., “NE” to “Northeast”) and product categories for uniform analysis.
  - Converted Revenue, Forecast, and Profit Columns to Numeric: Cast values as float for accurate calculations.
  - Filtered Data for Relevant Time Periods (2017-2019): Focused on these years to ensure a consistent analysis scope.
  - Grouped Data by Region, Category, and Subcategory: Organized the dataset into meaningful segments to analyze revenue trends by region and product category.

📍 Data: budget_project_data.csv

📊 Variance Analysis for 3-Year Budget Plan

For the period from 2017-2019, the analysis revealed several key insights into regional and product category performance:

  - Revenue Outperformance: Revenue exceeded forecasts by 6-7% each year. The Northwest region showed the highest variance, outperforming projections by 7.1%, while the Southwest region came in slightly lower, at 5.9%.
  - No Significant Patterns in Category Deviation: Although some categories showed sporadic deviations, these were not consistent enough to indicate a clear trend.
  - Forecasting Accuracy: Historically, forecasts have been conservative, leading to underestimation of actual revenue. The recommendation is to incorporate a 5% adjustment for revenue growth in future forecasts to better align actuals with projections.

3-Year Budget Forecast (2020-2022):

  Projected revenue growth: $19.24M (2020), $25.02M (2021), $32.65M (2022).
  The Electronics category is expected to dominate with 69% of the revenue, followed by Movies (12%) and Music (11%). 
  Books contribute around 8% to overall revenue.

🎯 Product Recommendation

Based on historical data analysis and forecasts, the following products and subcategories are recommended for growth focus:

  - Electronics:
        Focus on Video Equipment, TVs, Audio Equipment, and Cameras, as these subcategories consistently show high demand.
  - Movies:
        Prioritize Special Interest films, which have demonstrated steady growth.
  - Books & Music:
        Books: Focus on the Science & Technology subcategory.
        Music: Country music has shown consistent sales and is projected to grow.

Additionally, new product suggestions include:

  - Smart Home Devices: A rapidly growing market aligned with the rise of IoT.
  - Movie from Book Adoption: Creating synergy between the Books and Movies categories could attract a new customer base and increase engagement.

🔴 Risks & Challenges

  - Forecasting Accuracy: Although revenue forecasts have been improved, any deviation from a 5% growth assumption could lead to under/overestimation of resource allocation.
  - Supply Chain Issues: Disruptions in supply chains could delay product delivery and affect revenue growth, particularly for Electronics.
  - Market Volatility: Unforeseen economic downturns could impact consumer demand, particularly in discretionary categories like Movies and Music.

To mitigate these risks, careful monitoring of market trends and real-time data will be essential to adjust forecasts and strategic initiatives.

📊 Graphs

Developed a comprehensive 1-page PowerBI dashboard to visualize the following:

  - Graph 1: Total Revenue by Region (2017-2019):
     - Northeast had the highest revenue of $8.55M, followed by the South with $5.39M, and the Central region at $5.03M. The Northwest had the lowest revenue with $1.76M.
  - Graph 2: Total Revenue by Subcategories (2017-2019):
     - Electronics stood out with $24.4M in revenue, significantly outperforming other categories like Movies ($4.09M), Music ($3.9M), and Books ($2.64M).
  - Graph 3: Total Revenue Budget Forecast (2020-2022):
     - The revenue forecast for 2020 is $19.24M, increasing to $25.02M in 2021 and $32.65M in 2022.
  - Graph 4: Total Revenue Forecast by Region (2020-2022):
     - The Web sales channel is expected to generate the highest revenue ($48.8M by 2022), followed by the Northeast region with $14.95M, and the Central region with $9.7M. The Northwest region is forecasted to bring in $2.56M.
  - Graph 5: Total Revenue Forecast by Category and Subcategory (2020-2022):
     - Electronics continues to dominate the forecast with $52.88M by 2022, while Movies, Music, and Books are expected to contribute $8.94M, $8.42M, and $5.74M, respectively.

📍 Dashboard Link: [Dashboard to be embedded]
