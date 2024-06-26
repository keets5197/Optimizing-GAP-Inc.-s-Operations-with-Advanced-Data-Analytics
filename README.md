# Optimizing GAP Operations with Advanced Data Analytics

This project is a comprehensive case study on GAP Inc.'s transition towards data-driven decision making under the leadership of CEO Art Peck. The study focuses on three major brands under GAP Inc.: Gap, Banana Republic, and Old Navy, analyzing the strategic approaches, challenges, and outcomes of implementing data-driven strategies to combat declining sales and enhance customer experience.

## Contents

1. **PowerPoint Presentation (PPT)**
2. **Executive Summary**
3. **Jupyter Notebooks**

### Jupyter Notebooks

The Jupyter notebooks contain detailed analysis at the code level. The names and details of the Python files are as follows:

- **Social_Media_Analysis_Reddit.ipynb:** This file contains code for sentiment analysis from Reddit.
- **Google_Trends_Analysis.ipynb:** This file contains code for obtaining Google Trends data.
- **GAP_Reviews_Data_Mining.ipynb:** This file contains code for keyword analysis, opinion analysis of GAP reviews from the GAP website.
  - **Instructions:**
    1. Run the scraping code to generate a CSV file automatically.
    2. The code will read the generated CSV and perform text mining analysis.
- **amazon_hoodie_best_sellers.ipynb:** This file contains a regression model for predicting best-seller hoodie rankings on Amazon.
- **trustpilot_reviews.ipynb:** This file contains customer feedback analysis for Trustpilot reviews of Gap, Old Navy, and Banana Republic.
- **combined_output.ipynb:** This file contains the combined output for trustpilot_reviews.ipynb.
- **Sitejabber_last_12months_trend.ipynb:** This file contains the CSAT competitor trend analysis from Sitejabber reviews.

### Executive Summary

The Executive Summary contains the case introduction, analysis, process details, and conclusion in a summarized format.

## Overview

This case study delves into the following key aspects:

1. **Data-Driven Creative Process at GAP Inc.**
2. **Decision-Making Approaches**
3. **Competitor Analysis**
4. **Customer Feedback Analysis**
5. **Regression Modelling for Product Rankings**
6. **Recommendations and Limitations**


## Analysis Approach

### Data Sources
- Competitor Data
- Social Media
- Customer Reviews and Feedback
- Company Websites
- Consumer Behavior Data

### Analysis Techniques Utilised
- Text Analysis
- Time Series Analysis
- Sentiment Analysis
- Opinion Mining
- Key Word Analysis
- Regression Modelling

## Insights

### Regression Model

The regression model aimed to predict best-seller hoodie rankings on Amazon based on average rating, review count, and price.

**Equation:** 
\[ \text{Rank} = 10.9328 \times \text{Average Rating} - 0.0017 \times \text{Review Count} + 0.3059 \times \text{Price} \]

- R-squared value: 0.829, indicating that 82.9% of the variation in the dependent variable 'Rank' can be explained by the independent variables.

### Customer Feedback Analysis

**Platforms:** Trustpilot Reviews for Gap, Old Navy, and Banana Republic

- **Gap:** Positive reviews highlight quality and shopping experience; negative reviews focus on order processing and customer service.
- **Old Navy:** Frequent mentions of order-related issues and customer service.
- **Banana Republic:** Praised for online shopping experience and specific products; negative feedback on customer service and order issues.

**Key Insights:**
- Addressing low-rated reviews to improve quality, elevate ratings, and boost sales.
- Benchmarking against competitors like J.Crew and Shein for shipping and service features.

### Google Trends Analysis

- **Gap:** Interest is constant but has declined recently.
- **Old Navy:** Search trend decreases over time.
- **Banana Republic:** Trends increase over the past five years.

### Reddit Sentiment and Text Analysis

- Analysis of sentiment and discussions on subreddits relevant to fashion and brand reputation.

## Recommendations

1. **Utilize Negative Feedback:** Leverage insights from negative product reviews to address customer issues and improve products.
2. **Monitor Social Media:** Gauge customer sentiment and understand overall sentiment towards the company.
3. **Google Trends:** Incorporate trends data for strategic planning of discounting strategies and product launches.
4. **Innovative Designs for Banana Republic:** Focus on innovative designs to distinguish itself from competitors.

## Limitations

1. **Scalability:** Limited data sources; expanding data scraping could enhance insights.
2. **Sample Datasets:** Larger datasets from diverse sources could improve accuracy.
3. **Model Optimization:** Current models have room for improvement in complexity and parameter inclusion.

## Conclusion

The case study concludes that while all three brands can benefit from a big data approach, the application and focus might differ based on their target audience, price range, and style. A balanced approach integrating data-driven insights with creative decisions is recommended for optimal results.
