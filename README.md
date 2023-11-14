# Project US Election Prediction
U.S. Presidential Election forecasting has been a research interest for several decades. Currently, election prediction consists of two main approaches: traditional models that incorporate economic data and poll surveys, and models that leverage Twitter and other social media platforms due to their increasing popularity in the past decade. However, traditional approaches have predominantly focused on national-level predictions, while social media-based approaches often oversimplify the nuanced differences between online discourse and the broader voting population's political landscape. In this work, we perform a hybrid method of both the machine learning algorithm and the sentiment analysis on the state level with various independent variables including census data, economic indicators, polling averages, and the newly defined average sentiment scores from Twitter. Our prediction for the 2020 U.S. Presidential Election yielded promising results. Most of our models successfully predicted a victory for the Democratic candidate with 96\% accuracy using Gradient Boosting Trees and Multi-Layer Perceptron algorithms. This novel prediction framework addresses the limitations of existing U.S. Presidential Election forecasting approaches, particularly in terms of state-level predictions. It provides a valuable foundation for future research in this field and contributes to advancing our understanding of election dynamics.

## Data Variables
Census Data: our census data is collected from [United States Census Bureau](https://www.census.gov/data)

Economic Data: In this study, we use GDP and personal income percapita, our data source is .

Polling Data: We use the average of polling survey results corresponding to each state from August to election day in 2012, 2016, and 2020. For the 2012 polling surveys, the data are obtained from some polling reports, such as [YouGov](https://today.yougov.com/topics/politics/articles-reports) and [Public Policy Polling](https://www.publicpolicypolling.com/polls). For the polling surveys of 2016 and 2020, the data are extracted from [fivethirtyeight2016](https://projects.fivethirtyeight.com/2016-election-forecast/) and [fivethirtyeight2020](https://projects.fivethirtyeight.com/2020-election-forecast/).


Tweet Data: collected election related tweets dataset is stored in [our kaggle dataset](https://www.kaggle.com/datasets/matt0922/us-presidential-election-tweets)

## Data
- **Election Data** folder contains 2012, 2016, and 2020 U.S. Presidential Election related data.
- **ElectionPrediction.ipynb** file gives the details of our model configuration, data preprocessing, as well as prediction process.
