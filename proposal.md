# Obesity Explorer Dashboard

- Authors: Dustin Burnham, Javairia Raza, Rafael Pilliard Hellwig, Tanmay Sharma

## Section 1: Motivation and Purpose

Our role: Data science consultancy firm
 
Target audience: UN, WHO, government policymakers and project administrators, international aid agencies, researchers and public health professionals
 
Obesity has been an increasing medical concern across the world in the 21st century. It is a medical precursor to diseases such as diabetes, heart diseases, high blood pressure and certain types of cancers. With global proclivity towards stressful and fast paced lives and an unprecedented consumption of processed foods, obesity as a challenge has been garnering the attention of global health agencies.

We are a data science consultancy firm that specializes in global health and behavior. We propose to build a dashboard to present the historical trends of obesity over the last few decades across the different countries of the world. This unified view would help policy makers to identify the regions that warrant the most aid and elucidate upon some of the key factors driving the rise of obesity. Our dashboard aims to collate different visualizations that would help a policy maker to better plan their aid-budgets and resources vis-à-vis the obesity trends of the different countries.

## Section 2: Description of the data

The dataset we will be working with is related to potential factors associated with obesity for countries all around the world from 1975 to 2016. We have combined the (WHO obesity data)[https://www.who.int/data/gho/data/indicators/indicator-details/GHO/prevalence-of-obesity-among-adults-bmi-=-30-(age-standardized-estimate)-(-)] for each country with (World Bank indicators)[https://data.worldbank.org/indicator] data on income status, GDP, life expectancy, unemployment rate, debt risk and primary education completion percent by each year. We derived counts for these indicators by converting the rates and percents using population counts. Our final dataset has around 13,000 rows and all variables are stratified by year, country and sex. This will allow us to filter and aggregate data based on these different variables to determine differences in health outcomes and the associated risk factors for each. Overall, we are hoping to provide a more comprehensive picture on the patterns, high risk groups and trends on obesity and review the differences and similarities and differences between countries across time. We have also included longitude, latitude and capital of all countries to be able to visualize a map. From this dataset, we will derive rates of different factors (primary_ed_rate, obesity_rate, unemployment_rate) as well as ratios to compare differences across sex. Please see our initial EDA in our repository. 

## Section 3: Research questions and usage scenarios

## Section 4: Sketch of the App


## References

The World Bank (n.d.). Indicators. https://data.worldbank.org/indicator. Retrieved January 16, 2021, from https://data.worldbank.org/indicator

World Health Organization(WHO) (n.d.). Prevalence of obesity among adults, BMI = 30 (age-standardized estimate) (%). Retrieved January 16, 2021, from https://www.who.int/data/gho/data/indicators/indicator-details/GHO/prevalence-of-obesity-among-adults-bmi-=-30-(age-standardized-estimate)-(-)
