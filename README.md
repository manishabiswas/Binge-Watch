# Overview / Usage

A very classical solution when one thinks about Artificial Intelligence and Machine learning for content personalization is recommendation systems. We all know the “Netflix and chill” phrase which the most dedicated ‘Binge-watchers’ of the modern day dote upon. We bring an idea to interface this binge-watching with Alexa for PC.

The ‘Binge-watch’ is an Alexa skill for PC which recommends movies based on the movies a person has watched previously or has asked Alexa to search for. The idea is to create a simplistic, easy-to-follow method of creating this Alexa skill which while being very useful for all the movie fans, is a good sample for implementation of classic machine learning models using Alexa.

The Binge-watch reads plot summaries of Movies from IMDb and Wikipedia and tries to determine which movies the user would like to see next. It presents a very simple yet powerful business idea as the skill could be used to promote lesser known movies which cater to the interests of the users. The recommendation system runs on Intel Optimized Python.

# Methodology / Approach

The following is a sample of interaction with the Alexa skill for the user -

    User asks Alexa for movie recommendations
    Alexa asks what kind of movies the user likes - genres, sample movies
    Alexa comes up with recommendations
    Upon user feedback of how he/she liked the suggested movie, Alexa further learns about the user’s movie interests.

To achieve the above, we do the following -

    IMDb and Wikipedia are first scraped for movie plots and a movie similarity matrix is developed
    User’s liking is assimilated based on his interaction with Alexa, each user has a record in the database for the kind of movies he/she likes and has already seen
    Based on the similarity matrix, the new movie is recommended to the user.

# Technologies Used

    Alexa Skills for PC
    Intel Optimized Python
    Web Scraping
