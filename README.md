 ## Project Introduction
 
We've crafted an application capable of extracting tweets from Twitter. These tweets find their storage haven in AWS S3, where they seamlessly transition to AWS Glue for text transformation, ensuring optimal suitability for sentiment analysis and subsequent machine learning model training.

Leveraging Pyspark in Python and the AWS Glue environment facilitates the efficient transformation and manipulation of the tweet data.

Our journey doesn't stop there—sentiment analysis is diligently performed on the tweets, and we go a step further by constructing an ML model. This model is designed to predict the sentimental category of each tweet, adding a layer of depth to our project.

We're not shy about sharing the hurdles we overcame during the project, providing insights into the challenges encountered.

The project gracefully unfolds through five stages, each contributing to the overall success of our endeavor.

Stage 1: Retrieval and Storage on AWS S3
Retrieve tweets from Twitter using the boto3, tweepy, and snscrape libraries, and efficiently store them on AWS S3.

Stage 2: Preprocessing and NLP Analysis
Engage in the preprocessing of tweet texts and conduct in-depth analysis using Natural Language Processing (NLP) techniques.

Stage 3: Further Processing and ML Model Development
Leverage Spark within the AWS Glue environment for advanced processing of tweets in preparation for machine learning model development. Additionally, reprocessing and crafting of the ML model for predicting tweet sentiments will be undertaken in a Jupyter Notebook environment.

Stage 4: Logistic Regression Model Creation
Embark on the creation of a Logistic Regression model specifically designed to predict sentiment values for tweets.

Stage 5: Data Storage and Visualization with MongoDB
Implement the final stage by seamlessly sending data to MongoDB for storage and facilitating visualization, adding a robust layer to the overall project.


## Case Study

The Nigerian presidential election took place on February 25, 2023. In the lead-up to this pivotal event, a significant amount of political maneuvering and engagement unfolded on Twitter. Candidates, their supporters, and political parties actively participated in discussions and shared their perspectives on the platform. To meticulously monitor and analyze their activities on Twitter, searches were conducted within Twitter's fields to identify tweets containing mentions of political parties or their candidates. This data collection spanned from June 2022 to March 2023, capturing the dynamic discourse and interactions leading up to the election.

