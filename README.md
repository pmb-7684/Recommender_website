**Anime Recommendation System**
Group Project
Matt Carey, Kai Hansen, Paula M-Bailey, Steve Njoroge, and Mohammed Qurneh

[Complete jupyter notebook](https://github.com/kaihansen8/3162FinalProject/blob/main/Final_Group_Project.ipynb)

[Github repro ](https://github.com/kaihansen8/3162FinalProject)

[blog](https://kaihansen8.github.io/3162FinalProject/)

**Introduction**

With humble beginning that trace to late 19th century Japan, Anime has become global phenomenon captivating audiences.  As the number of titles grows, discovering new titles can be overwhelming.  This is where an anime recommender system can be beneficial.  

Our aim is to design a system to enhance the user’s experience by suggesting relevant shows and movies based on their taste and behavior patterns.  By analyzing viewer history, ratings, and behavior, we can identify patterns and similarities that could lead users to new titles. 

In this project, we focus on  building a content-based recommendation system. This system generates suggestions based on content that another user has previously enjoyed.  By using cosine similarity, we can compare features and identify those that match a user's interest and taste.  The goal is to create a way for users to discover new anime.  To evaluate the success of our recommendation system, we will test it out with members of our team and classmates.


**What is a Recommendation System?**

A recommendation system is an algorithm designed to suggest relevant products to a user based on the user’s behaviors, similarities with another user, and interests.  Products can include books, music, videos, customer satisfaction, etc.   


**How does it work?**

It begins with access to user data. Next, a content-based matrix is created based on the viewed anime titles and their ratings. A weighted feature matrix is computed using the user's matrix and the matrix containing all titles. This weighted features matrix is calculated using a similarity algorithm like cosine similarity, which determines how similar two vectors are to one another. The formula is as follows:


$Cosine Similarity(x,y) = \frac{x \cdot y}{||x|| \cdot ||y||}$


where:
- $x \cdot y$ is the dot product of vectors $x$ and $y$,
- $||x||$ is the magnitude (norm) of vector $x$,
- $||y||$ is the magnitude (norm) of vector $y$.


It measures the cosine of the angle between the vectors and produces a value between -1 and 1. A value of 1 suggests that 𝑥 and 𝑦 are very similar in tastes. A value of 0 suggests that 𝑥 and 𝑦 don’t share any interests, while a value of -1 suggests that 𝑥 and 𝑦 have opposite interests.

**Data Set**

Describe where you got your data. This could include obtaining the data through Kaggle or other resources, or scraping the data yourself somehow.

Also provide information about the dataset itself (what features, the size of the dataset, and any additional statistics or visualizations you create to better understand the data).

**Methods**

This should include descriptions of any pre-processing steps and the modeling. If you experiment by trying things out in different iterations, it is encouraged to also talk about all of that! What worked or what didn’t? Were you able to improve upon the model(s) or gain new insights through different iterations?

**Evaluation**

Based on your goal/model — how do you evaluate performance? What are the results?

For example, if you are running classification models, what are the accuracies, f1 scores, etc.? If you had questions in the introduction, were you able to answer them (discuss that)? etc.

Think about the best way to evaluate based on what you are trying to accomplish.

**Storytelling and Conclusion**

What insights did you gain through your project? Were you able to answer your initial problems? Obtain your initial goal? What stories can you tell? Do you have future steps in mind or things that could have been improved? ***For full credit here, you will need to show your critical thinking throughout.***

What have you learned throughout this project and the entire class?

**Impact Section**

Discuss the impact of your project. This can be socially, ethically, etc. It cannot be something like "our project has no impact" or "our project has no negative impact." Even the most well-intentioned projects *could* have negative impact. We will not be checking for "right" or "wrong" answers, but showing your critical thinking.
