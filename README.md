# Optimizing Real Estate Pricing Strategy for Maximized Profits.

![image](https://github.com/stephaniemwai/dsc-phase-2-project-v2-3/assets/143871178/ec0c4528-2217-4644-b7ca-78981466aa09)


## Project Overview:

Premiere Property Group, a prominent real estate agency in King County, has experienced a decline in profits over the past three years. To address this challenge, the agency has sought analytical expertise to devise a strategic pricing approach aimed at optimizing profits.

This initiative involves a deep dive into the vast array of housing data from King County, focusing on pivotal factors that influence house prices. Central to this analysis are variables such as the age of properties, their condition and ratings within different locations, the presence of views and waterfronts, and the impact of seasonal trends on sales.

The ultimate goal is to establish a comprehensive pricing strategy that not only maximizes profits for Premiere Property Group but also adapts to the fluctuating dynamics of the King County real estate market.

### General Objective:

To develop a comprehensive and data-driven pricing strategy that maximizes profitability for Premiere Property Group by thoroughly analyzing various factors influencing house prices in King County.

This general objective encompasses the overarching aim of the project, focusing on leveraging data analysis to enhance the agency's pricing approach in response to the recent decline in profits.

### Business Problem
In this project our main focus is the need to provide advice to homeowners about how home renovations might increase the estimated value of their homes, and by what amount. The following questions helped us in using exploratory analysis to analyse the data and give conclusive recommmendations for the homeowners. These include the following:
i) Does the age of the house(year built) have an impact on its selling price? Are there any patterns or trends that can guide pricing decisions?
ii) Is there a corelation between the condition/rating of a house, especially location and the resulting sales price?
iii) Is there a seasonal effect on the sales price of homes? For example, do homes sold during the winter season command higher prices compared to other months and how can this knowledge be leveraged for strategic pricing?
iv) What extent do the views and waterfront accessibility influence the property pricing? Does this feature impact overall value of the property.

Specific Objectives

**Age and Price Analysis:** Determine the impact of a house's age (year built) on its selling price and identify any significant patterns or trends that can be utilized in pricing strategies.

**Condition/Grade and Location Impact:** Assess the correlation between the condition or rating of a house and its sales price, especially considering the property's location, to understand how these factors influence valuation.

**Seasonal Pricing Trends:** Investigate if there are seasonal variations in house prices, particularly examining if houses sold in winter have different pricing dynamics compared to other seasons, and how this knowledge can be applied strategically.

**Effect of Views and Waterfront Accessibility:** Quantify the extent to which views and waterfront accessibility influence property pricing, and determine the value addition of these features to the overall property valuation.

**Waterfront Price Correlation Analysis:** Specifically analyze how the presence of a waterfront correlates with house prices and the premium it adds to property values.

**Grade Score Correlation Study:** Examine the relationship between the newly engineered grade score and selling prices, to understand how this metric reflects on property valuation.

These specific objectives are designed to address each of the research questions in detail, providing a structured approach to understanding the key drivers of house prices in King County. This approach will enable Premiere Property Group to make informed, data-backed decisions in their pricing strategies.

### The Data

Data

Utilizing the [king county data set ](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction?resource=download)  which encompasses details such as house size, location, condition, and various features, this project endeavors to construct an advanced multiple regression model. The primary objective is to develop a predictive model that can accurately estimate a house's price by incorporating the key factors. The emphasis is on optimizing the model's precision to enable effective predictions in the dynamic real estate landscape of King County.

### Column Names and descriptions for King County Data Set
* **id** - unique identified for a house
* **date** - Date house was sold
* **price** - Price is prediction target
* **bedrooms** - Number of Bedrooms/House
* **bathrooms** - Number of bathrooms/bedrooms
* **sqft_living** - square footage of the home
* **sqft_lot** - square footage of the lot
* **floors** - Total floors (levels) in house
* **waterfront** - House which has a view to a waterfront
* **view** - Has been viewed
* **condition** - How good the condition is ( Overall )
* **grade** - overall grade given to the housing unit, based on King County grading system
* **sqft_above** - square footage of house apart from basement
* **sqft_basement** - square footage of the basement
* **yr_built** - Built Year
* **yr_renovated** - Year when house was renovated
* **zipcode** - zip
* **lat** - Latitude coordinate
* **long** - Longitude coordinate
* **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors
  
### Findings, Conclusion & Recommendations:

![Finding](https://github.com/dukebaya/dsc-phase-2-project-v2-3/assets/133040698/6d75c8ed-4f47-41a4-9759-257f8572c31f)


Age of the house vs Price


![Age of house](https://github.com/dukebaya/dsc-phase-2-project-v2-3/assets/133040698/b8f32c27-88be-403a-aa64-7cea1a7becbe)

Grade vs Price


![Grade](https://github.com/dukebaya/dsc-phase-2-project-v2-3/assets/133040698/e4970079-63c2-4937-8563-7cbe2e399618)


Seasonal Pricing

![Seasonal Pricing](https://github.com/dukebaya/dsc-phase-2-project-v2-3/assets/133040698/173204b0-cb22-4c94-9668-8bd343112c56)


Location vs Price

![Location](https://github.com/dukebaya/dsc-phase-2-project-v2-3/assets/133040698/cb519cd4-7cbf-4840-bffc-7a0ec16d7ec7)


### Conclusion:
Positive Influencers on Price:

The presence of additional bathrooms, increased square footage, higher floors, waterfront access, captivating views, and elevated grade scores positively impact house prices. Notably, the inclusion of cities like Medina and Mercer Island in the analysis reveals their positive association with higher property values.

Negative Influencers on Price:

The number of bedrooms, certain city affiliations (e.g., Auburn, Federal Way, Kent), in reference to Bellevue, and specific features (e.g., Fall Season, City) exhibit a negative correlation with house prices. Premiere Property Group should be cognizant of these factors when devising pricing strategies.

Seasonal and Unique Factors:

While some seasonal variables do not significantly impact prices, it's crucial to note that the age of the house and the presence of a basement can influence pricing dynamics.

City-Specific Considerations:

Each city has a unique influence on house prices, emphasizing the need for tailored strategies for different locations

Based on the comprehensive analysis of the King County housing data, here are the final recommendations and opportunities for further analysis:

## Final Recommendations:

Dynamic Pricing Strategy:
Implement a pricing strategy that accounts for property size (especially living area square footage), location (specific zipcodes and cities), and property features (like condition and grade).
Emphasize premium features like large living spaces, desirable locations, views, and waterfront access in pricing and marketing efforts.

Seasonal Marketing and Sales Tactics:
Capitalize on the higher market activity and prices in Spring and Summer for listing and selling properties.
Consider more competitive pricing and marketing strategies in Fall and Winter to attract buyers during slower market periods.

Location-Focused Investment:
Identify and invest in areas with high-demand zipcodes and emerging markets.
Leverage insights from location-based analysis to make informed decisions about property acquisitions, developments, or renovations.

Data-Driven Decision Making:
Continue to use data analytics for informed decision-making in all aspects of real estate transactions, from pricing to marketing to investment strategies.

### Opportunities for Further Analysis:

Micro-Location Trends:
Conduct a deeper analysis at a neighborhood level within specific zipcodes or cities to uncover more nuanced market trends and investment opportunities.

Long-Term Market Trends:
Analyze historical data over several years to understand long-term trends in the real estate market, including price appreciation rates in different areas.

Economic and Demographic Factors:
Incorporate broader economic indicators and demographic data to understand how macroeconomic conditions and population trends impact the real estate market.

Advanced Predictive Modeling:
Employ more advanced machine learning techniques, such as gradient boosting or neural networks, for more accurate price predictions and market trend analysis.

Impact of Renovations:
Investigate how different types of renovations and improvements impact property values, which could guide investment decisions for property upgrades.

Customer Segmentation and Targeting:
Use data analytics to segment potential buyers or renters and tailor marketing strategies to different target groups.

Impact of External Factors:
Assess the impact of external factors such as new infrastructure developments, zoning changes, or policy shifts on local real estate markets.
By continuously leveraging data analytics and staying attuned to market trends, Premiere Property Group can maintain a competitive edge in the dynamic King County real estate market.

## Authors 
[Philip Mweri] (https://github.com/dukebaya)

[Chepkemoi Ruto] (https://github.com/LCR2022)

[Moses Wanja] (https://github.com/moseskigo)

[Mark Kamau] (https://github.com/BigmanMKG)

[Stephanie Mwai] (https://github.com/stephaniemwai)

[Miriam Ongare] (https://github.com/Miriam-Ivy)
