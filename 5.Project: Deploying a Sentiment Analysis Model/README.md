# Sentiment Analysis Deployed on AWS 

Recurrent neural network is utilized to to build a sentiment analysis model on Movie Reviews data. This Model is developed on AWS on Amazon SageMaker. 

Users can interact with the model through a web Webapp.

In order for SageMaker to interact with the web app, 'sentiment_lambda_function' is deployed on AWS Lambda service which is inturn called via API Gateway.

##Webapp :
![webapp](https://github.com/TensorAdy/udacity_dlnd/blob/master/5.Project:%20Deploying%20a%20Sentiment%20Analysis%20Model/webapp/Screen%20Shot%202020-06-28%20at%2018.33.06.png)
![webapp](https://github.com/TensorAdy/udacity_dlnd/blob/master/5.Project:%20Deploying%20a%20Sentiment%20Analysis%20Model/webapp/Screen%20Shot%202020-06-28%20at%2018.37.57.png)

#### Trying real world reviews on IMDB

![imdb](https://github.com/TensorAdy/udacity_dlnd/blob/master/5.Project:%20Deploying%20a%20Sentiment%20Analysis%20Model/webapp/Screen%20Shot%202020-06-28%20at%2018.40.10.png)
![app](https://github.com/TensorAdy/udacity_dlnd/blob/master/5.Project:%20Deploying%20a%20Sentiment%20Analysis%20Model/webapp/Screen%20Shot%202020-06-28%20at%2018.39.59.png)
