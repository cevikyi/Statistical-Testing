Data Preparation and Cleaning: In my notebook, I start by loading and examining a dataset, where I identify initial observations such as unusual price ranges, future registration years, and negative stock days. I then address missing values, convert data types, and resolve logical inconsistencies. This includes removing duplicated records and recalculating metrics like CTR (Click-Through Rate).

Exploratory Data Analysis (EDA): I conduct a thorough EDA, focusing on the distribution of variables like search views and detail views, and identifying patterns in listing deletions. My EDA includes transforming skewed data for better analysis and investigating trends and anomalies in the dataset.

T-Test (ttest_ind from SciPy.stats): This statistical test, which I use to compare the means of two independent groups, is a crucial part of my analysis. I employ it to assess whether there are significant differences in metrics like search views or click-through rates between different categories of products or listings.

Regression Analysis (using statsmodels.api): I use regression analysis to understand the relationships between different variables in the dataset. For instance, I analyze how various factors like listing duration, price, or product category influence the number of views or click-through rates.
