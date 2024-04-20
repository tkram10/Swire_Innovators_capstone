# Swire Innovators
### Business problem statement

Swire Coca-Cola has faced major challenges in managing production and inventory for its new products, Starlight and Dreamworld. Each product showed different patterns in sales, highlighting the need for better forecasting and planning. Starlight had solid sales for the first 30 weeks, but then sales dropped due to problems getting enough syrup for production. This issue prevented the company from making as much profit as it could have, even though there was strong media support and public interest that could have increased sales even more. On the other hand, Dreamworld started with high sales that quickly fell after just 14 weeks. This drop wasn't because of supply problems but because the company made too much product, expecting higher demand. This resulted in too much stock and financial losses.

These challenges have made it clear that Swire Coca-Cola must improve how it predicts demand and adjusts production quickly. As Swire plans to launch seven new products, applying these improvements is essential. By doing so, the company aims to manage inventory levels better and prevent running out of products or producing too much, thereby saving costs and satisfying customers. This strategic approach will be crucial in successfully introducing the new products and avoiding the pitfalls experienced with Starlight and Dreamworld.

### Impact

By accurately predicting demand for Swire Coca-Cola's innovative products, we ensure resources are used efficiently, preventing waste and saving costs. This ensures we have the right products available when customers want them, leading to happier customers and strengthened loyalty to our brand. 
With increased customer satisfaction and loyalty, we can drive more sales, capture new market opportunities, and increase profitability. 
Ultimately, by understanding and meeting consumer demands effectively, we enhance operational efficiency and strengthen our brand's reputation, driving sustainable growth in the competitive beverage industry.

#### Analytical Approach.
This problem can be addressed in multiple approaches:

Approach-1 :

Identify regular products that closely resemble the specified innovative products and forecast sales by leveraging the sales data of these similar products.
Determine the most relevant similar products based on factors such as brand, market category, manufacturer, package type, and flavor, matching the specifications of the specified innovative products.
Analyze the weekly sales figures of these similar products.
Aggregate the sales data of these products to predict the sales of the innovative products.

Approach-2 :

This involves segmenting the success of regular products according to demographics and regions. By identifying patterns and public sentiments, we can analyze the weekly sales of these specific items within those regions. This sentiment analysis will forecast the sales of these specified innovative products.

### Findings

#### IMAGE-1: Unit sales and dollar sales for each manufacturer.

<img width="1217" alt="Screen Shot 2024-04-20 at 11 38 42 AM" src="https://github.com/tkram10/Swire_Innovators_capstone/assets/72302122/99bc30d1-efbc-4acf-8504-2b599b18faf4">

COCOS and JOLLYS are the most prolific manufacturers, with unit sales as high as 1 to 1.2 million and dollar sales around 3 to 5 million. In contrast, KEKES, BEARS, and JORDYS have notably lower sales, around 0.1 million units, compared to the others. PONYS and ALLYS have significant sales of around 0.5 million units. SWIRE-CC, with more than 0.8 million unit sales and around 3 million in dollar sales, secures third place in the market after COCOS and JOLLYS

#### IMAGE-2: Market size of SWIRE-CC over time.

<img width="1025" alt="Screen Shot 2024-04-20 at 11 45 51 AM" src="https://github.com/tkram10/Swire_Innovators_capstone/assets/72302122/5f95a5ec-0eae-4b23-a123-e063d0e9d678">

We can see only the SWIRE-CC sales over time, and SWIRE has sales peak in November and December every year due to Christmas and Thanksgiving; also, the sales increase in May and June every year. We mainly consider SWIRE-CC to be the manufacturer in our analysis, as SWIRE-CC is the only manufacturer in our modeling questions.

#### Contribution to the project

I was crucial in managing data importation into Google Cloud Storage and Google Colab and executing complex SQL queries via Google BigQuery. I conducted extensive data analysis, including creating a correlation matrix heatmap and analyzing market and packaging trends to correlate them with sales data. I developed forecasting models using techniques such as Prophet, ARIMA, SARIMA, and Exponential Smoothing for three innovative products. Additionally, I compiled all findings into a comprehensive report and ensured accuracy by proofreading the entire notebook. My contributions also included researching the most effective models for our forecasting needs and ensuring our analytical approaches were robust and well-suited to the project's objectives.


