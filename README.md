# Swiggy_data_analysis

🥡 **Swiggy Restaurant Data Analysis** 🍽️

📌 **Overview**

This project dives into the diverse world of food delivery using real-world restaurant data scraped from Swiggy. With a dataset enriched with information like restaurant names, food categories, prices, ratings, delivery times, and customer reviews, we explore key questions that define urban food consumption habits and restaurant performance.

🎯 **Objective**

To uncover insights and trends hidden within restaurant offerings, customer preferences, and service dynamics — all through statistical analysis, data distributions, and visual storytelling.

🔍 **Key Findings**

1. 🍽️ The Food Landscape

North Indian, Chinese, and Biryani top the charts as the most commonly offered food types.

However, the most loved cuisines by rating include Mughlai and Continental, hinting that popularity doesn't always equal quality.

2. 🏙️ City & Area Dynamics

Cities like Bangalore and Hyderabad dominate in restaurant density.

Yet, customer satisfaction (via ratings) varies by area, with some lesser-known localities delivering top-tier experiences.

3. 💸 Pricing Patterns

The pricing distribution shows that most restaurants are budget to mid-range.

Higher prices don’t necessarily equate to higher ratings, suggesting that affordability often matches customer expectations.

4. 🚚 Delivery Time Analysis

Most orders are delivered within 30–40 minutes, with long delivery times being outliers.

Areas with longer average delivery times may be suffering from logistical or traffic constraints.

5. ⭐ Customer Ratings Behavior
   
Average restaurant ratings cluster tightly between 3.5 and 4.5, showing consistent service standards.

Restaurants with more total ratings generally reflect trustworthy, well-established businesses.

📊 **Visual Insights**

This project includes 15+ targeted visualizations to explore:

Top 10 food types by count and by average rating

Rating, price, and delivery time distributions

City and area comparisons

Correlations between price and delivery time, and rating behavior

📊  **Understandings:**

1. Distribution of Restaurant Prices
   
Q: What is the price distribution of restaurants?

A: A histogram shows how prices are spread — whether most restaurants are budget-friendly or expensive. A right-skewed distribution means many low-cost places and few costly ones.

2. Distribution of Average Ratings

Q: How are average ratings distributed?

A: Most ratings typically cluster around 3.5–4.5. A histogram helps identify whether ratings are inflated (very high) or realistic (normal spread).

3. Distribution of Delivery Times

Q: How long do deliveries take across restaurants?

A: This helps evaluate customer wait times. A bell-shaped curve shows consistency; long tails suggest outliers (very slow delivery).

4. Number of Restaurants per City

Q: Which cities have the most restaurants?

A: A bar plot answers this, highlighting city-wise competition and availability. It may show metro areas like Bangalore or Delhi dominate.

5. Distribution of Total Ratings

Q: How many people rate each restaurant?

A: Some have 10,000+ ratings; others may have just a few. This shows trustworthiness — more ratings usually mean more reliable averages.

6. Top 10 Most Common Food Types

Q: Which food categories are most commonly offered?

A: After multi-label encoding, summing each binary food type column gives total mentions. Popular types like North Indian, Chinese, or Biryani likely top the list.

7. Price by City

Q: How do restaurant prices vary across cities?

A: Box plots help compare price ranges. Some cities may have higher median prices due to cost of living or premium dining culture.

8. Average Ratings by City

Q: Do customers in some cities give higher ratings?

A: Comparing rating distributions city-wise reveals regional satisfaction trends. It also shows where food quality or service is appreciated more.

9. Price vs. Average Rating

Q: Do expensive restaurants have higher ratings?

A: A scatter plot shows if a trend exists — higher price = better rating — or if it's unrelated. This tests value-for-money perceptions.

10. Delivery Time vs. Total Ratings

Q: Do longer delivery times affect customer engagement (ratings count)?

A: This helps explore if slow delivery deters customers from rating, or from ordering again. No clear trend may mean delivery doesn’t impact review behavior directly.

11. Average Ratings in Top 5 Areas

Q: Which areas have the best-rated restaurants?

A: Local area-wise boxplots show regional quality trends. Some neighborhoods may be known for good food and better service.

12. Do Expensive Restaurants Get Better Ratings?

Q: Is there a correlation between cost and customer satisfaction?

A: Grouping prices into quartiles (cheap to premium) and plotting their average ratings tests if higher price yields better experience.

13. Areas with Longest Average Delivery Times

Q: Which areas consistently suffer long deliveries?

A: A bar chart highlights logistical inefficiencies or high-traffic areas. Useful for Swiggy's ops team or customer expectation management.

14. Food Types with Highest Average Ratings

Q: Which food types do people love most?

A: By averaging ratings across all restaurants that offer each food, we identify food styles people rate highly — e.g., Mughlai might beat Fast Food.

15. Correlation Between Delivery Time and Price

Q: Are expensive meals slower to deliver?

A: A scatter plot shows whether higher-priced meals (e.g., fine dining) tend to have longer delivery times due to prep time or packaging.


🛠️ **Technologies Used**

Pandas for data manipulation

Seaborn and Matplotlib for visualization

Scikit-learn’s MultiLabelBinarizer for encoding multi-label food categories

✅ **Takeaway**

This analysis uncovers not just what people eat, but where, how fast, and how satisfied they are across urban India. It bridges food analytics with customer experience, offering actionable insights for delivery platforms, restaurant chains, and even curious foodies.
