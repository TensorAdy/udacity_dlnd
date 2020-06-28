# Sentiment Analysis Deployed on AWS 

Recurrent neural network is utilized to to build a sentiment analysis model on Movie Reviews data. This Model is developed on AWS on Amazon SageMaker. 

Users can interact with the model through a web Webapp.

In order for SageMaker to interact with the web app, 'sentiment_lambda_function' is deployed on AWS Lambda service which is inturn called via API Gateway.

