# IMDb Regression

**Goal of the project**
The core objective of this project is to predict the revenue for each movie through the actor score.


## pre-work

1.  Web Scrapping two website IMDB Website and Numbers website.
2.  Dropped all duplicated rows and unneeded columns.
3.  Removed nulls.
4.  Converting object-type columns into numeric.

The number of columns and rows before cleaning were **51 and 10,000** After cleaning up the data the number of columns and rows are **24 and 1500**

<img src="https://github.com/Madahus4/project-2/blob/main/heatmapforIMDB.png" width="600"/>

The correlation between all numeric columns was calculated. As shown in the heatmap graph there are a lot of columns that are highly correlated with another for example Budget and Worldwide Gross.

<img src="https://github.com/Madahus4/project-2/blob/main/budget.%20per%20gross.png" width="600"/>

you can notice in the above graph athe high correlation  between budget with gross, the adventures movies had the highest budget.

## Future work:
building a **Linear Regression Model** to predict the revenues.