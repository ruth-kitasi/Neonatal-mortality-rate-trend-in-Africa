# Neonatal mortality rate trend in Africa

### Dashboard Link : https://app.powerbi.com/groups/me/reports/fcb93a96-65fd-4990-8e17-08a62113ec33/ReportSection?experience=power-bi


## Unravelling the NMR trend Africa though PowerBI vizualization

Join me as I embark on a journey of data exploration into the neonatal health landscape in Africa, where I am drawn to the heart of the subject matter, “the very cradle of life”. Beyond the numbers, lies a narrative that is shaped by the delicate balance between birth and survival.

In this analysis, I will delve into the multifaceted realm of neonatal health in Africa, seeking to unveil insights that not only inform but inspire action towards ensuring a thriving start for the continent’s youngest and most vulnerable population.


### What is Neonatal mortality rate?

As you peruse this article, you might find yourself pondering the mysterious term “neonatal health”. Hold off on that Google search, because the answer’s just a scroll away. Neonatal health refers to the health and well-being of newborn infants during the first 28 days of life

![infant](https://github.com/ruth-kitasi/Neonatal-mortality-rate-trend-in-Africa/assets/106556092/b588c301-6653-4e39-a825-594c7ceb46a5)

### Objectives.
-Identify trends the NMR in Africa.

-Identify countries with the highest and lowest NMR.

-Determine causes of neonatal mortality.

-Determine factors affecting incline and decline of NMR in particular countries.

### Factors to consider analysis.
-Determining the source of dataset for the analysis.

-Identifying tools for data cleaning and modelling.

-Determining relevant variable to answer questions.

### Source of dataset for analysis.
There are various sources of neonatal health data. For this analysis, I will download the datasets from the data.unicef.org. UNICEF data team offers data on children on various aspects.

### Tools for data cleaning and modelling.
I have chosen Microsoft excel as a tool to perform cleaning on the dataset. Firstly, the downloaded data shows NMR for all the countries in the world from 1968 to 2021.

![image1](https://github.com/ruth-kitasi/Neonatal-mortality-rate-trend-in-Africa/assets/106556092/7d0fab25-dd89-46d7-9844-d605212a1966)

For this analysis I will explore neonatal health of 5 years, from 2017–2021 as shown in the snippet below.

### Identifying relevant variable in the dataset for analysis.
I will generate the average uncertainty bonds of each country for each year to work with a less complex datasets using the subtotal feature under the data menu.

![image2](https://github.com/ruth-kitasi/Neonatal-mortality-rate-trend-in-Africa/assets/106556092/f7562f4e-aabc-4fce-9731-c1916de19b61)
I will further clean this set, by copying the visible cells using the following steps:-
highlight the entire data set.

click on Control + G

from the popup, click on special and select visible cells only.

Click Ok.

Copy the visible cells and paste in a new location.

![Image3](https://github.com/ruth-kitasi/Neonatal-mortality-rate-trend-in-Africa/assets/106556092/0485337d-30de-4dc0-9105-12eaa2a30937)

Although I am focusing on neonatal health in Africa, you will realize that the above table comprises neonatal mortality rate of all countries in the world. In this case, I will have to use a V-LOOKUP function with a lookup tables comprising of countries and continents, to finds Africa continents for my datasets.

![image4](https://github.com/ruth-kitasi/Neonatal-mortality-rate-trend-in-Africa/assets/106556092/c693b3d2-b787-45d3-bf50-a519826a8a93)

Now, having the continent column, I will apply a filter on the continent column to get Africa NMR only, and copy these results to a separate worksheet, ready for Power BI analysis.

![image5](https://github.com/ruth-kitasi/Neonatal-mortality-rate-trend-in-Africa/assets/106556092/b90ea918-f1a5-44ed-86c0-e79075cf8a5c)

### Uploading dataset on Power BI
For the power BI dataset upload, I have created a master sheet with all the necessary column for analysis to assist me in generating and normalizing tables to reduce redundancy.

![image6](https://github.com/ruth-kitasi/Neonatal-mortality-rate-trend-in-Africa/assets/106556092/ad07d306-f8fb-45f3-bc17-7ab564526898)

### Creating Data Models.
A data model is a representation of the relationships between different tables of data which serve as the foundation for creating interactive and meaningful and dashboards. From my master sheet, I will create three separate table, NMR table, territories table and population table and linked them using primary keys.

Establishing relationships between tables will allow me to connect and combine data from multiple sources, enabling a more sophisticated and insightful analysis.

![image7](https://github.com/ruth-kitasi/Neonatal-mortality-rate-trend-in-Africa/assets/106556092/0b5982b6-8ba6-4921-aa8f-052b9c21356c)

### Building an interactive Power BI dashboard.
Once the relations are well related, now it it time to build a dashboard for my analysis. There are several metrics in my dashboard that I want to show for easy communication. These are:-

-Total population in Africa.

-NMR per 1,000 lives.

-Top ten countries with the highest NMR.

-Top ten countries with the lowest NMR.

-Average decline/incline rate


I will also include slicers to filter and compare specific years, regions and countries.
### Creating measures using DAX expressions.
I have created new measure to calculate the average neonatal mortality rate that I will use in the report.
Power BI Visual Report.

![image8](https://github.com/ruth-kitasi/Neonatal-mortality-rate-trend-in-Africa/assets/106556092/3019993e-af53-4a2b-92fe-e956593dc73a)

The snippet below shows results of the NMR in Africa for a period of 5 year.

![image10](https://github.com/ruth-kitasi/Neonatal-mortality-rate-trend-in-Africa/assets/106556092/d498c572-eb25-42a4-ac40-cd3906b08248)
### Observations
From the analysis, I can conclude that over the five year(2017–2021) there has been an avg decline 0.20% in NMR. This can be backed-by the combination of factors reflecting improvements in healthcare, socio-economic conditions, and public and private health interventions.

South Sudan has the highest mortality rate due to the complex set of challenges that contribute to this rate. To mention but a few factors are conflict and political instability, limited healthcare infrastructure and limited access to skilled birth attendants.
Improving maternal and neonatal health outcomes in South Sudan requires a comprehensive approach that addresses factors contributing to the increased rate and so is the remedy for the other countries experiencing a higher NMR.

###  Conclusion
The observed improvements in neonatal mortality rate across Africa, signal a promising trend towards enhanced maternal and child well-being. In the resent years, concerted efforts from the public, private and development sectors, have contributed to positive shifts in neonatal health outcomes on the continent. These improvements underscore a commitment to fostering a healthier start for the youngest members of society.
