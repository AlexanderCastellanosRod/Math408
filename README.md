# Math408

# Mobile Dataset Project Proposal

## Group Members
- **Alex Castellanos Rodriguez**  
  - Group Role: Leader  
  - Project Role: Data Wrangler  
- **Leslie Soto**  
  - Group Role: Communicator  
  - Project Role: Dashboard Designer  
- **Alyssa Claro**  
  - Group Role: Scheduler  
  - Project Role: Model Builder  

## Title
**Mobile Dataset Analysis & Price Prediction**

## Purpose
The mobile phone market is highly competitive, with various brands offering devices across different price ranges. This project analyzes mobile phone features (e.g., RAM, storage, camera quality, battery) and predicts pricing using machine learning.

### Key Questions
- What are the most critical factors influencing mobile phone prices?
- Can we build a predictive model to estimate the price of a mobile based on its specifications?
- How do different brands position their products in terms of price and features?
- What trends can be identified in mobile phone pricing for 2025?

## Data
We are using the [Mobiles Dataset](https://www.kaggle.com/datasets/abdulmalik1518/mobiles-dataset-2025) from Kaggle, containing:
- 930 entries
- 10 variables (6 numerical, 4 categorical)
- Formats: CSV

### Variables
- **Numerical**: RAM (GB), Battery (mAh), Front Camera (MP), Back Camera (MP), Screen Size (inches)
- **Categorical**: Brand, Model, OS Type, Processor Type
- **Target Variable**: Price (USD)

## End Product
- **Price Prediction Model**: Regression model to estimate mobile phone price.
- **Feature Importance Analysis**: Understand which specifications affect price most.
- **Market Trends Dashboard**: Interactive visualization of brand-based trends.

## Technical Stack
- Dataset: Kaggle CSV
- Language: R
- Tools: RStudio
- Libraries: `tidyverse`, `ggplot2`, `caret`, `shiny`

## Hosting & Deployment
Our final deliverables and dashboard will be hosted on this GitHub Pages site:  
🔗 [Project Site URL](https://yourusername.github.io/mobile-dataset-project)

## Challenges
- Handling missing values and ensuring data quality
- Managing outliers in pricing data
