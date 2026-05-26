Capstone Project Problem statement : Perform sentiment analysis on Omnicron variant, data fetching directly from twitter Sentiment analysis is the process of identifying feelings and emotions expressed in words, through ML or AI

Project Pipeline

Various steps in completing project are

Import Necessary Dependencies

Read and Load the Dataset

Exploratory Data Analysis

Data Visualization of Target Variables

Data Preprocessing

Splitting our data into Train and Test Subset

Transforming Dataset using TF-IDF Vectorizer

Function for Model Evaluation

Model Building

Conclusion

Here we have to get dataset directly fetched from twitter in realtime

performing realtime sentimental analysis on realtime data collecting from twitter

objective: perform sentiment analysis on realtime data collected from twitter

API (Application Programm Interface) Imagine you’re sitting at a table in a restaurant with a menu of choices to order from. The kitchen is the part of the “system” that will prepare your order. What is missing is the critical link to communicate your order to the kitchen and deliver your food back to your table. That’s where the waiter or API comes in. The waiter is the messenger – or API – that takes your request or order and tells the kitchen – the system – what to do. Then the waiter delivers the response back to you; in this case, it is the food.

API's are huge and are used everywhere

In simple words api stands as bridge for one to access the content in one's storage

There are many APIs on the Twitter platform that software developers can engage with, with the ultimate possibility to create fully automated systems which will interact with Twitter. While this feature could benefit companies by drawing insights from Twitter data

From twitter api it's possible to extract many insights some are

Tweets: searching, posting, filtering, engagement, streaming etc.

Accounts and users (Beta): account management, user interactions.

Media: uploading and accessing photos, videos and animated GIFs.

Trends: trending topics in a given location.

Geo: information about known places or places near a location.

Getting twitter API keys

If you don't already have an account, you can login with your normal Twitter credentials

follow the required prompts to create a developer project or click here Click here

Requesting the API key and secret via the Developer Portal causes Twitter to produce the following three things:

API key (this is your 'consumer key') API secret key (this is your 'consumer secret') Bearer token Next, visit the 'Authentication Tokens' area of the Developer Portal and generate an 'Access token & secret'. This will provide you with the following two items: Access token (this is your 'token key') Access token secret (this is your 'token secret') Expected output

the data fetched from twitter should undergo EDA for analyzing, cleaning, handling, manupulation, visualization..,etc final output should show the sentiment of the data Some tips to consider

Machines can learn in every possible way so its always better to think out of the box

Perform eda as diverse as possible and in contineous manner

Try configuring with diffrent models to know how each model is diffrent with other ones

Donot try to involve unneccesory codes and useless algorithms for dataset which just increases complexity

Approaching problem statement in n number of ways helps us to find best one possible

It's easier for one to understnd and manupulate if we have models as simple as possible

When we have multiple models we can have multiple judgements based on models and their efficiencies

Tuning helps increasing accuracy :)

Have an idea of time consumed by the model, its better to have a model whose time management is good

Spend good amount of time on analyzing dataset and draw as much insights as possible

Tweepy is importantlibrary we will using to fetch data from twitter by api
