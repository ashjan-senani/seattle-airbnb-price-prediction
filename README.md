# Seattle Airbnb Price Prediction

## Project Overview
This project aims to predict the price of Airbnb listings in Seattle using machine learning techniques. By analyzing key features such as location, number of rooms, amenities, and guest reviews, we aim to understand the factors that influence Airbnb pricing. The ultimate goal is to provide insights that help Airbnb hosts optimize their pricing strategies based on data-driven findings.

## Business Problem
Airbnb hosts often face challenges in setting the right price for their listings, especially in a competitive market like Seattle. This project aims to address the following business questions:
- What factors influence the price of Airbnb listings in Seattle?
- How can we predict the price of an Airbnb listing based on features such as location, amenities, and reviews?
- Which features have the greatest impact on pricing decisions for Airbnb hosts?

## Modeling Approach
We used machine learning techniques to predict the prices of Airbnb listings based on various features. The steps followed in the analysis were:

1. **Data Collection**:
   - We utilized the Seattle Airbnb dataset, which contains information on over 10,000 listings. The dataset includes features such as price, location, amenities, and guest reviews.

2. **Data Preprocessing**:
   - We handled missing values by using appropriate methods such as imputation or dropping rows with missing critical information.
   - Categorical variables were encoded using techniques like one-hot encoding to make them suitable for machine learning models.

3. **Feature Engineering**:
   - We identified key features that have a significant impact on pricing decisions, including location, number of rooms, guest reviews, and amenities. This step was crucial to enhancing the predictive power of the model.

4. **Modeling**:
   - Linear regression was chosen to predict the prices of Airbnb listings. This approach helps us understand how each feature affects the price and allows us to build a reliable model.

5. **Evaluation**:
   - We evaluated the model's performance by comparing predicted prices to actual prices. We used metrics like mean squared error (MSE) and R-squared to assess the model's accuracy.

## Results
The analysis revealed several key insights into the factors that affect Airbnb pricing in Seattle:
1. **Location**: Listings in more central or desirable neighborhoods, such as Capitol Hill and Downtown Seattle, tend to have higher prices.
2. **Size of the Property**: Larger properties, with more rooms and beds, are generally priced higher.
3. **Guest Reviews and Ratings**: Listings with higher ratings and more positive guest reviews are often priced higher, reflecting their quality and reputation.

The predictive model demonstrated a reasonable degree of accuracy in estimating prices based on these factors.

