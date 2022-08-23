# Clustering_sentiment_Zomato
ZOMATO RESTAURANT CLUSTERING AND SENTIMENT ANALYSIS

India is quite famous for its diverse multi cuisine available in a large number of restaurants and hotel resorts, which is reminiscent of unity in diversity. The growing number of restaurants in every state of India has been a motivation to inspect the data to get some insights, interesting facts and figures about the Indian food industry in each city. So, this project focuses on analyzing the Zomato restaurant data for each city in India. Different clustering algorithms are used in the project to help in finding the best clusters with maximum accuracy.

The Project focuses on Customers and Company. One has to analyze the sentiments of the reviews given by the customer in the data and made some useful conclusion in the form of Visualizations. Also, cluster the Zomato restaurants into different segments. The data is visualized as it becomes easy to analyze data at instant. 

Different approaches have been experimented for determining the number of optimum clusters. Further the efficacy of the clusters model is validated using classification machine learning model, and the best clustering method according to the validation results is chosen and to understand feature importance, SHAP explainer was used.

The cuisines data for each restaurant were having too many distinct cuisines. Converting them to limited categories with similar cuisines was a better choice for moving forward. KPrototype method of clustering produced good results with f1 score of 0.91 for actual values and 0.93 for normalized values.

The most important feature was cost, with overseas type categories as a second important feature. Overseas category included Chinese, Asian, and Italian cuisines. 

Top words from the corpus of positively rated reviews are, 'good, ‘food', 'place', 'order', 'service', 'chicken'. Top words from the corpus of negatively rated reviews are, 'food', 'order', 'place', 'service', 'chicken'. Top words from the corpus of neutral rated reviews are, 'good’, ‘food', 'place', 'order', 'taste', 'chicken'.

By Sentiment by top words analysis it was observed that, words with highest positively rated fraction are place, ambience. And words with highest negatively rated fraction are order, taste.

