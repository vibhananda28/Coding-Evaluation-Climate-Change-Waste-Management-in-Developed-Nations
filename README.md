# CLIMATE CHANGE AND WASTE MANAGEMENT: A DIVE INTO HOW THE DEVELOPED COUNTRIES MANAGE WASTE
Climate change is often linked to the dooms day that bestows upon the world today. Waste generation and management is known to be a leading cause of global warming. Developed countries have more resources at their disposal to treat waste appropriately and are yet known to generate more waste than the developing economies. We find more guides than analysis to evaluate how the developed world is managing its waste. In this project, we focus on how developed countries manage and treat waste and how it is related to some economic factors like education attainment, population density and poverty. We are going to use a variety of visualizations and data analysis tools. 
## DATA 
1. We have 2 datasets: World Bank's [World Development Indicators](https://databank.worldbank.org/source/world-development-indicators) and [OECD waste database](https://stats.oecd.org/Index.aspx?DataSetCode=WSECTOR) (data ranges from 1990-2021).

2. Variables include: Education expenditure by government, total educational attainment (at least until bachelor's degree), educational attainment for women, poverty statistics, population growth and levels, Forest coverage, GDP per capita (real) and growth, municipal waste generation, % material recovery (recycled + composting).

## HYPOTHESIS AND ANALYSIS
#### HYP 1: 
Electronic waste generation per capita and % of material recovery have a strong relationship with education. We will use both education attainment and education expenditure statistics to evaluate the relationship. 

#### HYP 2: 
We expect the waste production trend to be downwards and recovery % to be upwards, especially post 2015 when all UN members agreed to UN’s Sustainable Development Goals (Goal 13: Climate action- Take urgent action to combat climate change and its impacts). The Paris Climate Change Agreement was also launched in 2015 making the hypothesis more sound. 

#### HYP 3: 
We expect some co-integration between waste generation and forest cover depletion. We will explore the relationship between the two to draw some insights. We will strive to use both [WB](https://databank.worldbank.org/source/world-development-indicators) and [OECD](https://stats.oecd.org/Index.aspx?DataSetCode=WSECTOR) data for this.

#### ANALYSIS 1: 
We can take different variables (like population density, electronic waste, municipal waste generated) and countries to create a birpartite graph with variables on one side and countries on the other. In this hypothesis we will test which variables are most related to each other on the basis of homophily and link prediction. 

## CONCLUSIONS
To be added

## CITATIONS
##### DATA:
1. World Bank WDI: https://databank.worldbank.org/source/world-development-indicators
2. OECD: https://stats.oecd.org/Index.aspx?DataSetCode=WSECTOR

##### REGEX: 
3. https://regexr.com/631qa
4. https://www.w3schools.com/python/python_regex.asp

##### RESHAPING:
4. https://stackoverflow.com/questions/37418295/wide-to-long-data-transform-in-pandas
5. https://stackoverflow.com/questions/50856183/pandas-wide-to-long-the-id-variables-need-to-uniquely-identify-each-row
6. https://pandas.pydata.org/docs/reference/api/pandas.wide_to_long.html
7. https://towardsdatascience.com/reshaping-a-pandas-dataframe-long-to-wide-and-vice-versa-517c7f0995ad
8. https://stackoverflow.com/questions/43756052/transform-pandas-pivot-table-to-regular-dataframe

##### MERGE:
9. https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.merge.html

##### DTYPES: 
10. https://www.geeksforgeeks.org/python-pandas-dataframe-dtypes/
11. https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.astype.html

##### PLOTS: 
12. https://github.com/AbhishaPT/2022Spring_Finals
13. https://datagy.io/python-correlation-matrix/
14. https://datatofish.com/correlation-matrix-pandas/
15. https://www.geeksforgeeks.org/plotting-graph-using-seaborn-python/
16. https://seaborn.pydata.org/tutorial/introduction
