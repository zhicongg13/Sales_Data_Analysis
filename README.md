# Analysing Super Store Sales Data with Python

Tools and libraries: 
* Python (Jupyter Notebook)
* Data Exploration (Pandas)
* Data Visualisation (Matplotlib, Seaborn)

Super Store Dataset obtained from: https://www.kaggle.com/datasets/laibaanwer/superstore-sales-dataset 

Project Overview:
This project analyses Super Store's sales data to uncover valuable performance insights. It is organised into five key analytical areas, each tailored to address specific questions and identify areas of improvement. 

# 1. Time Analysis:

### 1.1 What is the trend of sales over the years?
The graph shows a consistent and positive growth trend in sales over the years from 2011 to 2014 - which is a positive sign for Superstore, as it shows that they are able to continue to grow their business.

<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/1.1%20What%20is%20the%20sales%20trend%20over%20the%20years%3F.png">
 </kbd> <br>


### 1.2 Which month has the highest sales, and how does it compare yearly?
Based on the trend of the sales figures during the months of January to May, with February consistently exhibiting the lowest total sales, implementing targeted promotions and activities during this period can help stimulate sales and drive customer engagement. Here are some promotion ideas:

1. Seasonal Sales Events:
* Launch special seasonal sales events or clearance sales during the months of January to May to attract customers seeking discounts and deals - such as 1/1, 2/2 and 3/3 monthly promotional sales.

2. Holiday Promotions (Tailored for February):
* Create promotional campaigns around holidays like Valentine's Day and Lunar New Year to capitalise on increased consumer spending during these periods.
* Offer themed promotions, bundle deals, or exclusive discounts for holiday-related products.
  
<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/1.2%20Which%20month%20has%20the%20highest%20sales%2C%20and%20how%20does%20it%20compare%20yearly%3F.png">
 </kbd> <br>

<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/1.2%20Which%20month%20has%20the%20highest%20sales%2C%20and%20how%20does%20it%20compare%20yearly%3F%20(2).png">
 </kbd> <br>
 

# 2. Geographical Analysis:
### 2.1 How has consumer segment growth varied regionally from 2013 to 2014?
* The top 3 regions with the highest growth are Africa (68%), EMEA (50%) and Central Asia (36%).
* The lowest 3 regions with the lowest growth are East (2%), Caribbean (5%) and Oceania (6%).
  
<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/2.1%20How%20has%20consumer%20segment%20growth%20varied%20regionally%20from%202013%20to%202014%3F.png">
 </kbd> <br>


### 2.2 What are the top 3 regions with the highest and lowest customer counts?

The data shows that Central Asia is in the bottom third of the lowest customer count. However, it is also one of the top three regions with the highest growth from 2013 to 2014, as shown in the previous analysis.

* Highest customer count: Central, South and EMEA.
* Lowest customer count: Canada, Caribbean and Central Asia.

<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/2.2%20What%20are%20the%20top%203%20regions%20with%20the%20highest%20and%20lowest%20customer%20counts%3F.png">
 </kbd> <br>



### 2.3 How do sales trends in Central Asia vary, and what surges were observed from 2013 to 2014?

The trendline of Central Asia displays patterns of growth and decline throughout the year, except for October. In 2013, sales experienced a sharp decline, while in 2014, there was a significant growth surge. It would be worthwhile for Superstore to investigate the promotional campaigns implemented during October 2014.

<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/2.3%20How%20do%20sales%20trends%20in%20Central%20Asia%20vary%2C%20and%20what%20surges%20were%20observed%20from%202013%20to%202014%3F.png">
 </kbd> <br>





# 3. **Shipping Analysis**:
### 3.1 Which shipment mode is the most popular?
The most popular shipment mode is Standard Class, accounting for 60% of all shipments.

* Standard Class 30775 (60%)
* Second Class 10309 (20%)
* First Class 7505 (14%)
* Same Day 2701 (5%)

<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/3.1%20Which%20shipment%20mode%20is%20the%20most%20popular%3F.png">
 </kbd> <br>




### 3.2 Does the type of shipment mode affect the shipping date?
The shipment mode does affect the duration, below are the average shipping durations.

* Standard Class (5 days)
* Second Class (3 days)
* First Class (2 days)
* Same Day (0 day)

<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/3.2%20Does%20the%20type%20of%20shipment%20mode%20affect%20the%20shipping%20date%3F.png">
 </kbd> <br>




### 3.3 What is the total shipping cost customers have paid over the years?

The total shipping costs paid by customers over the years are as follows:

* Standard Class: $614630
* Second Class: $314112
* First Class: $308103
* Same Day: $115974
  
A special promotion to boost sales could offer a 50% discount on standard class delivery. Given that standard class delivery is the most popular shipping option, Superstore can capitalise on it to temporarily increase their sales by enticing customers to purchase. 

<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/3.3%20What%20is%20the%20total%20shipping%20cost%20customers%20have%20paid%20over%20the%20years%3F.png">
 </kbd> <br>



# 4. **Product Analysis**:
### 4.1 Which product category has sold the most? (In quantity)

* Office Supplies have sold the most in quantity: 108,282 (60%).
* Followed by Technology: 35,176 (19%)
* Lastly, Furniture: 34,954 (19%)

<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/4.1%20Which%20product%20category%20has%20sold%20the%20most%3F%20(In%20quantity).png">
 </kbd> <br>



### 4.2 Which product category has sold the most? (In sales amount)

* Technology has the most in sales amount: $4,744,691 (37%),
* Followed by Furniture: $4,110,884 (32%),
* Lastly, Office Supplies: $3,787,330 (29%).

<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/4.2%20Which%20product%20category%20has%20sold%20the%20most%3F%20(In%20sales%20amount).png">
 </kbd> <br>




### 4.3 What is the sales trend for each product category?
In terms of sales quantity, all three product categories have consistently increased their sales throughout the years. However, when examining the line plot, the Furniture and Technology segments have shown a plateauing trend compared to the Office Supplies category.

It is intriguing that while Office Supplies has the highest quantity of items sold, it ranks the lowest in total sales figures. Conversely, Technology products contribute significantly to overall sales despite having the lowest quantity sold. This can be attributed to the higher unit prices of technological gadgets.

Overall, quantity and sales figures have exhibited a steady upward trajectory throughout the years.

<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/4.3%20What%20is%20the%20sales%20trend%20for%20each%20of%20the%20product%20category%3F.png">
 </kbd> <br>


<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/4.3%20What%20is%20the%20sales%20trend%20for%20each%20of%20the%20product%20category%3F%20(2).png">
 </kbd> <br>


### 4.4 Do different product categories exhibit consistent sales patterns across different markets?

Market-Specific Observations:

* APAC: Furniture and technology lead in sales volume within the overall market. However, office supplies rank second highest, falling behind the EU. This suggests there is potential for growth in the office supplies product category in the APAC region.

* Canada: The Canadian market constitutes less than 1% of the total sales percentage compared to other markets, which is concerning. Due to the significantly low sales volume, Superstore may need to evaluate the viability of continuing operations in this market.

<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/4.4%20Do%20different%20product%20categories%20exhibit%20consistent%20sales%20patterns%20across%20different%20markets%3F.png">
 </kbd> <br>

<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/4.4%20Do%20different%20product%20categories%20exhibit%20consistent%20sales%20patterns%20across%20different%20markets%3F%20(2).png">
 </kbd> <br>


# 5. **Profit Analysis**:
### 5.1 Which top 3 countries have the highest profit? 
Text
Text




### 5.2 Which top 3 countries have the lowest or negative profit?
Text
Text




### 5.3 Which product sub-categories result in negative sales profits, and in which top 5 countries are they occurring?
Text
Text
<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/5.3%20Which%20product%20sub-categories%20are%20resulting%20in%20negative%20sales%20profits%2C%20and%20in%20which%20top%205%20countries%20are%20they%20occurring%3F.png">
 </kbd> <br>

 
<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/5.3%20Which%20product%20sub-categories%20are%20resulting%20in%20negative%20sales%20profits%2C%20and%20in%20which%20top%205%20countries%20are%20they%20occurring%3F%20(2).png">
 </kbd> <br>



### 5.4 How many customers are generating profits or losses?
Text
Text
<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/5.4%20How%20many%20customers%20are%20generating%20profits%20or%20losses%3F.png">
 </kbd> <br>



### 5.5 Are there any customers who qualify as regular customers by placing at least 100 orders in the store, and if so, are they profitable for the business?
Text
Text
<p align="center"> <kbd> <img width="700" alt="Presentation1" src="https://github.com/zhicongg13/Sales_Report_Data_Analysis/blob/main/Graphs/5.5%20Regular%20customers%20profit%20and%20loss.png">
 </kbd> <br>












