# Online user purchase prediction

# Overview
This is my exploration of a website’s online user dataset to predict which online users visiting the website are more likely to make a purchase. This project is part of Harvard’s CS50 “Introduction to Artificial Intelligence with Python” course. In the big scheme of things, determining the purchasing habits of a person visiting an online shopping website could inform what products to recommend to them. You can get the dataset [here]( https://cdn.cs50.net/ai/2020/x/projects/4/shopping.zip)

# Solving the problem
After much fine-tuning, I built a k-nearest neighbor classifier that produced an accuracy score of 86%. However, since the data did not have a lot of the online visiting customers making a purchase, an accuracy score of 86% doesn’t really say much, only that it can correctly predict customers who would not make a purchase. So, in order to determine how the model performs in identifying which customers will make a purchase, I built a function to determine the sensitivity and specificity of the model. In this, the model was only 29.14% sensitive, and 96.66% specific. That is, the model was only able to accurately predict which customers would make a purchase 29.14% of the time. Is this a particularly good model, I think it is a start. 
