Aerofit Treadmill Customer Analysis — End-to-End Case Study

This project analyzes how customer characteristics influence the choice of treadmill model at Aerofit. Using a dataset of 180 customers, the study combines descriptive analytics, exploratory data analysis, probability modeling, and customer segmentation to uncover the key drivers behind product preference across Aerofit’s three treadmill models — KP281, KP481, and KP781.

**Project Objectives**
The analysis answers the central business question:

“How do customer characteristics influence the choice of treadmill purchased?”

To solve this, the project:
Builds detailed customer profiles for each model.
Performs univariate, bivariate, and correlation analysis.
Constructs marginal and conditional probability models.
Identifies the most influential factors affecting product choice.
Provides data-driven marketing and product strategy recommendations.

**Dataset Overview**

Rows: 180
Columns: 9
Variables: Product, Age, Gender, Education, Marital Status, Usage, Fitness, Income, Miles
No missing values detected.
Categorical variables converted to appropriate data types. 

** Key Analytical Insights**
1. Customer Segmentation by Product
KP281 — Entry Level

Gender-balanced (50% Male / 50% Female)
Young adults (mean age ≈ 28.6)
Lower income (~$46K)
Intermediate fitness levels
Moderate weekly usage (~83 miles)

KP481 — Mid Range

Slight male skew
Similar age and fitness to KP281
Moderate income (~$49K)
Usage patterns similar to entry model

KP781 — Premium

82.5% Male buyers
Higher income (~$75K)
Highest fitness levels (mean 4.62)
Heavy weekly miles (~167 miles)

**Correlation Highlights**

Fitness ↔ Miles: Strong (0.79)
Usage ↔ Miles: Strong (0.76)
Income ↔ Fitness & Usage: Moderate
Age: Weak relationships overall

**Probability Findings**

Marginal Probabilities

KP281: 44.44%
KP481: 33.33%
KP781: 22.22%

Key Conditional Probabilities

P(KP781 | Male) = 32%
P(KP481 | Age < 30) = 29%
P(KP281 | Income < 50K) = 58%
P(KP781 | High Fitness) = 94% (strongest predictor) 


**Business Recommendations**

KP281 — Entry-Level
Target: Budget-conscious young adults
Messaging: Affordability & simplicity
Offer: Entry bundles, financing options

KP481 — Mid-Level
Target: Upgraders, intermediate users
Messaging: Value-for-money
Offer: Warranty bundles, comparison-based marketing

KP781 — Premium
Target: High-income, advanced users (mostly male)
Messaging: Performance, durability, elite experience
Offer: Personalized training, premium accessories
