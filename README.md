# Recommendation-Engine-with-IBM
A recommendation engine developed utilizing IBM Watson Studio Community user data for better article recommendations 

------

## Note:
Since the user matrix file is too large to be uploaded through the browser on github, a download the link to that file is [here](https://drive.google.com/file/d/1FupIzJfkgOdEGF9b6GM6nO4u4HT27ofD/view?usp=sharing). Download it and keep it in the same directory as the main jupyter notebook.

----

## Project Motivation
IBM has an online data science community where members can post tutorials, notebooks, articles, and datasets. In this project, you will build a recommendation engine based on user behavior and social network data, to surface content most likely to be relevant to a user.

----

## I. Exploratory Data Analysis
Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.

-----

## II. Rank Based Recommendations
To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

----

## III. User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

----

## IV. Matrix Factorization
Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with. You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.

----

## V. Extras, Content Based Recommendations & Conclusion
Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

As other work to show off your skills, you can configure your code into a class and deploy your code to a flask app. Alternatively, you could deploy using Heroku. Again, these steps are not required to complete the project, but can help you push your skills and show off your work to the world.

---

If you do find this repository useful, why not give a star and even let me know about it!

Feel free to express issues and feedback as well, cheers!

