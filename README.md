📊 BikeWale EDA Project – PPT Content
Slide 1: Title Slide

Title: Exploratory Data Analysis (EDA) on BikeWale Dataset

Subtitle: Insights into Bike Prices, Performance & Trends

Your Name & Details (e.g., Prasad, MCA 2024)

Slide 2: Introduction

BikeWale is a platform providing details about bikes (price, performance, mileage, reviews).

Aim: Perform EDA to understand bike specifications, pricing trends, and consumer preferences.

Why EDA? → Helps in decision making, comparison & recommendations.

Slide 3: Objectives

Collect bike data (name, price, CC, BHP, weight, mileage, ratings).

Clean and preprocess data.

Explore relationships between bike features.

Identify market trends (price range, fuel efficiency, etc.).

Provide insights for buyers and manufacturers.

Slide 4: Dataset Information

Source: BikeWale website (scraped using Python & BeautifulSoup).

Features:

Bike Name

Price (Ex-showroom & On-road)

Engine CC

BHP (Power)

Mileage (Kmpl)

Weight

Ratings & Reviews

Location & Colors

Slide 5: Tools & Libraries

Python

Pandas, NumPy (Data Handling)

Matplotlib, Seaborn (Visualization)

BeautifulSoup, Requests (Web Scraping)

Jupyter Notebook (Analysis & Visualization)

Slide 6: Data Cleaning

Removed missing values.

Converted data types (Price → Numeric, Mileage → Float).

Handled inconsistent formats (e.g., "₹ 1.5 Lakh" → 150000).

Dropped duplicates.

Slide 7: Exploratory Data Analysis (EDA)

Distribution of bike prices.

Top bike brands by number of models.

Correlation between engine CC, BHP & Price.

Mileage comparison across bikes.

Customer rating analysis.

Slide 8: Visualizations

(Use graphs here)

Histogram: Bike price distribution.

Bar Chart: Top brands with most bikes.

Scatter Plot: Engine CC vs Price.

Box Plot: Mileage spread across brands.

Heatmap: Correlation between CC, BHP, Price.

Slide 9: Key Insights

Higher CC and BHP → Higher Price.

Mileage mostly between 35–50 kmpl for mid-range bikes.

Royal Enfield, Honda, and Bajaj dominate the Indian market.

Customer ratings don’t always match bike price (some budget bikes have high ratings).

Slide 10: Conclusion

EDA revealed strong patterns in performance, mileage, and pricing.

Useful for customers (choosing bikes) and manufacturers (understanding market trends).

Future Work: Predictive modeling for bike price recommendation.

Slide 11: References

BikeWale Website

Python Libraries Documentation
