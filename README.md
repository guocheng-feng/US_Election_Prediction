# Project US Election Prediction
U.S. Presidential Election forecasting has been a research interest for several decades. Currently, election prediction consists of two main approaches: traditional models that incorporate economic data and poll surveys, and models that leverage Twitter and other social media platforms due to their increasing popularity in the past decade. However, traditional approaches have predominantly focused on national-level predictions, while social media-based approaches often oversimplify the nuanced differences between online discourse and the broader voting population's political landscape. In this work, we perform a hybrid method of both the machine learning algorithm and the sentiment analysis on the state level with various independent variables including census data, economic indicators, polling averages, and the newly defined average sentiment scores from Twitter. Our prediction for the 2020 U.S. Presidential Election yielded promising results. Most of our models successfully predicted a victory for the Democratic candidate with 96\% accuracy using Gradient Boosting Trees and Multi-Layer Perceptron algorithms. This novel prediction framework addresses the limitations of existing U.S. Presidential Election forecasting approaches, particularly in terms of state-level predictions. It provides a valuable foundation for future research in this field and contributes to advancing our understanding of election dynamics.

## Data Variables
Census Data:
Economic Data
Polling Data:

## Data
- **Election Data** folder contains 2012, 2016, and 2020 U.S. Presidential Election related data.
- **ElectionPrediction.ipynb** file gives the details of our model configuration, data preprocessing, as well as prediction process.
