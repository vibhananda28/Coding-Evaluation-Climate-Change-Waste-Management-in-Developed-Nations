# CLIMATE CHANGE AND WASTE MANAGEMENT: A DIVE INTO HOW THE DEVELOPED COUNTRIES MANAGE WASTE
Climate change is often linked to the dooms day that bestows upon the world today. Waste generation and management is known to be a leading cause of global warming. Developed countries have more resources at their disposal to treat waste appropriately and are yet known to generate more waste than the developing economies. We find more guides than analysis to evaluate how the developed world is managing its waste. In this project, we focus on how developed countries manage and treat waste and how it is related to some economic factors like education attainment, population density and poverty. We are going to use a variety of visualizations and data analysis tools. 

## DATA 
1. We have 2 datasets: World Bank's [World Development Indicators](https://databank.worldbank.org/source/world-development-indicators) and [OECD waste database](https://stats.oecd.org/Index.aspx?DataSetCode=WSECTOR) (data ranges from 1990-2021).

2. Variables include: Education expenditure by government, total educational attainment (at least until bachelor's degree), educational attainment for women, poverty statistics, population growth and levels, Forest coverage, GDP per capita (real) and growth, municipal waste generation, % material recovery (recycled + composting).

## HYPOTHESIS AND ANALYSIS
#### HYP 1: 
Electronic waste generation (overall and per capita) as well as percent of material recovery have a strong relationship with education. We believe that developed countries should have higher material recovery rates given the resources at their disposal. Additionally, we also believe that more educated people generate more electronic waste given the affordability and higher use of technology. We will use both education attainment and education expenditure statistics to evaluate the relationship. 

#### HYP 2: 
We expect the waste production trend to be downwards and recovery % to be upwards, especially post 2015 when all UN members agreed to UN’s Sustainable Development Goals (Goal 13: Climate action- Take urgent action to combat climate change and its impacts). The Paris Climate Change Agreement was also launched in 2015 making the hypothesis more sound. 

#### HYP 3: 
We expect some co-integration between waste generation and forest cover depletion. We will explore the relationship between the two to draw some insights. We will strive to use both [WB](https://databank.worldbank.org/source/world-development-indicators) and [OECD](https://stats.oecd.org/Index.aspx?DataSetCode=WSECTOR) data for this.


## CONCLUSIONS

#### HYP 1: 
We analyzed trends for each country, correlation overall for all countries for all years and also individually for each country. Overall, there were no strong , noteworthy correlations found. For material recovery, our hypothesis for confirmed given that most countries had a positive correlation between material recovery and education related variables. Most countries also had an upward trending curve over the years. For electric waste generation, the correlation was not apparent. However, based on the trends available, our hypothesis was confirmed as most countries had an upward trending curve. More details are noted in the notebook. 

#### HYP 2:
Decreasing waste production trend and increasing recovery% were observed for some countries namely Belgium, Germany, Spain, United Kingdom, Hungary, Japan, Korea, Netherlands, Australia, and Estonia. Apart from them for other countries we either observe that both the variables increase simultaneously (strong correlation) or have a weak correlation between them. Therefore, hypothesis 2 is true only for the countries listed above while it fails in other cases. 

#### HYP 3: 
Countries like Portugal, Mexico, Canada, and Colombia show an increasing trend of waste production while their forest cover depletes over the course of time. Furthermore, countries like Germany, Spain, the United Kingdom, Hungary, and Turkiye exhibit an increasing trend in forest areas while their waste production decreases over time. Apart from them for other countries we either observe that both the variables increase simultaneously (strong correlation) or have a weak correlation between them. Therefore, hypothesis 3 is true only for the countries listed above while it fails in other cases. 


## NOTE: 
We would like to note that we understand that correlation does not prove causation. Panel data regression or Machine Learning models to understand further causation or relationships between the variables was beyond the scope of this project. However, we intend to draw some insights to aid future studies through our analysis. 

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

##### JUPYTER NOTEBOOK: 
12. https://stackoverflow.com/questions/20186344/importing-an-ipynb-file-from-another-ipynb-file
13. https://docs.qubole.com/en/latest/user-guide/notebooks-and-dashboards/notebooks/jupyter-notebooks/running-jupy-notebooks.html#running-a-jupyter-notebook-from-another-jupyter-notebook

##### PLOTS: 
14. https://github.com/AbhishaPT/2022Spring_Finals
15. https://datagy.io/python-correlation-matrix/
16. https://datatofish.com/correlation-matrix-pandas/
17. https://www.geeksforgeeks.org/plotting-graph-using-seaborn-python/
18. https://seaborn.pydata.org/tutorial/introduction
19. https://engineeringfordatascience.com/posts/matplotlib_subplots/
20. https://stackoverflow.com/questions/71403746/creating-time-series-plots-with-the-countries-as-subplots
21. https://python.quantecon.org/pandas_panel.html

##### STATISTICS: 
22. https://www.geeksforgeeks.org/python-pearson-correlation-test-between-two-variables/
