# Bikeshop Exploratory Data Analysis
## Executive Summary of this Business Case
Our bicycle company is experiencing stagnant growth due to inefficient and ineffective marketing. We sought to address this by analysing our visitors' data to identify customer characteristics associated with a higher propensity to purchase a bike. Therefore, using Python, I analyse the datasets to create a heuristic concept of our customer.

## Project Personal Purpose & Reasons on why I chose these datasets.
During my bachelor's, I had a hard time applying all the abstract theoretical concepts from my notebook. I felt I wasted so much time studying, but I never applied anything in the real world.
As I am currently pursuing my master's in business analytics, I find that projects provide an immediate application of what we learn in the programme, helping me build a strong foundation and deepen my engagement with the materials.
Therefore, in this project, I will conduct an **Exploratory Data Analysis** to improve managerial decision-making.

I chose these datasets because I currently live in the Netherlands, where everyone bikes. Whether you are old or young, married or single, no matter your ethnicity or race, you are controlled by this invisible hand to get around on a bicycle. This prompts me to explore any correlations with characteristics.

## Goal
To learn customer behaviour based on their characteristics to see who has a higher propensity to buy a bike, which may help the business understand the customer more, such as marketing departments, target marketing to customers who have a higher propensity to buy, creating ads that target that specific customer group.

## Deliverables
Data Dictionary

![image.png](https://github.com/4damtick/Bikeshop-ExploratoryDataAnalysis/blob/main/Datadictionary.png?raw=true)

## Results, Business Recommendation, Caveats.
Starting with our continuous variables, we find that *Children, Car*, and *Age* are negatively correlated with the propensity to purchase a bicycle. This can indicate that people who are having more children are more likely to use a car, as it is easier for them. Car variable, on the other hand, might show people who have a car are less likely to buy a bicycle, as a car is more convenient for their mobility purposes. Lastly, an age-negative association is logical as people who are older have lower physical capabilities to bike. In our categorical variables, we can see that *Education, Commute* and *Region* have notable Cramers' V values with respect to the willingness to buy a bicycle, which implies a strong relationship between categorical variables and our dependent variable. Education may be due to the fact that educated people are more likely to be aware of the positive environmental impact of biking compared to driving a car, thus driving up this relationship. Commute might be due to the fact that people who need to travel far to the office are less likely to bike. Lastly, the region where our customers might drive up the willingness to bike with reasons such as the cycling infrastructure, the awareness of the society, and many more regional factors. Looking at the problem from a business perspective, we now understand more of the characteristics of people who have a higher willingness to buy this item, such as a higher education level, a lower commute to work, a smaller number of children, not having a car, a young age, and living in the European region.

Therefore, from understanding these customer characteristics, we can do a lot of things for our event campaign. For example, we can partner up with businesses to supply them with bikes for their employees who live closer. We can offer big discounts for students, and many more. The caveats, however, we don't know how worth it it is, as people who have a higher propensity to buy might still buy with or without the discount, while people who do not have these characteristics may benefit more, and therefore it is more beneficial to target them instead. This is a field that is not discussed; however, this analysis can be implemented in that way by using tools from causal inference, such as a directed acyclic graph, or any other tools that can be used to isolate the effect of these characteristics on their propensity to buy a bike.








