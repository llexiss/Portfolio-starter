# The base of the project
This academic research is entirely based on using [the dataset from Kaggle](https://www.kaggle.com/datasets/mokar2001/house-price-tehran-iran)  

# Our team
There is no I in team - I wouldn't have done this project without my great friends ([Lisa](https://github.com/ElizavetaTarTar) and [Azat](https://github.com/gachibek))

# What this project is about?
We're studying the real-estate market in Tehran

# What this project is for?
The aim of this study is to determine the dependency of housing prices on their characteristics, using the example of Tehran, the capital of Iran. Before starting the work, we set the following main objectives:

- Study the necessary literature on the research topic
- Collect and process data on housing prices in Tehran  
- Evaluate and select a model that best describes the impact of various characteristics on housing prices in Tehran  
- Formulate and analyze hypotheses related to housing prices in Tehran  
- Identify which characteristics actually affect housing prices in Tehran  
- Examine how certain housing characteristics influence its price in Tehran  
- Determine the contribution of specific characteristics to housing prices in Tehran  

The study uses data on housing prices and their characteristics in Tehran, the capital of Iran. The data was sourced from the Kaggle website (aggregated by Mohammadreza KarimiNejad in 2021 from an Iranian real estate website during his house search).  

The dataset contains information about 3,474 houses in Tehran with comprehensive descriptions.

# Variables used in the research

**Target Variable:**  
Price (USD): The price of real estate in US dollars - the decisive factor when purchasing property.

**Explanatory Variables:**  
• Area: A key pricing factor. Larger area generally correlates with higher prices.  
• Room: (Number of bedrooms): Reflects the functionality and suitability of the property for family living. A higher number of bedrooms typically increases the price.  
• Parking: The availability of parking. In urbanized areas, parking spaces are a valuable resource that raises property prices.  
• Warehouse: Additional storage space can increase the price, although its effect may be weaker compared to parking or an elevator.  
• Elevator: The presence of an elevator increases convenience and the liquidity of the property, especially in multi-story buildings.  
• Region: Location is one of the primary factors in the model. Different districts may have varying infrastructure, prestige, access to transportation, etc., which influence the price.

This set reflects the main property characteristics commonly used in hedonic models, based on theoretical and empirical insights from the real estate market.

# Preliminary Data Analysis Includes the Following Sections:  
1. Analysis of Statistical Outliers  
2. Descriptive Statistics  
3. Correlation Matrix  
4. Visualization

# Regression Models:  
1. Unadjusted Multiple Linear Regression Model  
2. Adjusted Multiple Linear Regression Model: with removal of detected outliers  
3. Logarithmic Model: aimed at reducing data variability  
4. Model with Stepwise Removal of Non-Informative Variables: aimed at reducing the impact of multicollinearity among explanatory variables

# Hypotheses:  
1. **Hypothesis of Diminishing Marginal Utility of Area:**  
   "As the housing area increases, its marginal utility for buyers decreases, meaning that additional square meters increase the price less significantly."  
   Justification: Similar to patterns noted in studies, it can be assumed that the marginal effect of increasing area diminishes as the area grows.  

2. **Hypothesis of Regional Differences (District):**
   "There are consistent price differences between districts that cannot be explained solely by apartment infrastructure: district prestige, proximity to the city center, transport accessibility, and other implicit factors increase housing prices in some districts compared to others."  
   Justification: Regions act as proxies for a combination of external factors influencing housing demand and supply.

# Conclusions  

In the course of this study, we analyzed the cost of apartments in Tehran (Iran) and the factors influencing it. The results showed that, as expected, area has the most significant positive impact on housing prices. Additionally, the hypothesis of diminishing marginal utility of area was not confirmed: there is insufficient evidence to assert that additional space provides increasingly smaller price increments.  

The use of logarithmic transformation of variables improved the model's quality, demonstrating the effectiveness of reducing sensitivity to outliers and normalizing the data. Stepwise variable selection revealed that the most significant combinations include area, location in the Pardis district, the presence of an elevator, number of rooms, and a storage unit. The inclusion of additional variables, such as parking, only slightly improved the model.  

The study confirmed that the main characteristics of housing and its location play a key role in determining real estate prices in Tehran. At the same time, the minor impact of certain variables and specific outliers indicate the need for further data refinement and a deeper analysis of the market's unique features.
