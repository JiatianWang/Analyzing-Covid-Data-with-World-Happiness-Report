# Analyzing-Covid-Data-with-World-Happiness-Report
## Objectives

* Understanding the purpose of the project, the datasets that will be used, and the questions that will be answered with the analysis.
* Importing COVID19 and World happiness report 2020 dataset preparing it for the analysis by dropping columns and aggregating rows.
* Finding and calculating a good measure for the analysis.
* Merging two datasets and finding correlations among the datasets.
* Visualizing analysis results using Seaborn.

## Research question

Is there any relationship between the spread off the covid19 in the country and how happy people are living?

Two working datasets:
* Coivd19 dataset which consists of the data related to a cumulative number of confirmed cases in different countries per day.
* Word happiness report which consists of scores given by people, those people who are living in different countries to various life factores, such as freedom to make life choses
healthy life expectancy,social support ans so on.

I am going to merge these two data sets and calculate a measure which can help us to find the answer and I will visualize the results

## Visualizing data related to countries of interest

* Confirmed cases with time 

![1](https://user-images.githubusercontent.com/32876600/95692153-34289c80-0bf2-11eb-8264-c71f268f9337.JPG)

* Growth rate

![2](https://user-images.githubusercontent.com/32876600/95692154-35f26000-0bf2-11eb-888a-d5a5a122a71f.JPG)
* Correlation Matrix with heatmap

![3](https://user-images.githubusercontent.com/32876600/95692156-37bc2380-0bf2-11eb-885f-aae35b4716bb.JPG)

* Plotting GDP VS maximum infection rate

![4](https://user-images.githubusercontent.com/32876600/95692158-38ed5080-0bf2-11eb-850a-829a03a7dee5.JPG)

![5](https://user-images.githubusercontent.com/32876600/95692160-3a1e7d80-0bf2-11eb-9ab6-d73cfea662d7.JPG)

## Conclusion

As a result off this analysis, I would like see if there is any correlation between the columns related to different life and columns that represent the spread of the virus in each these countires
I found the factors that correlate with maximun infection rate. I have the all positive correlations between all of other life factors, but they are all week correlation.
