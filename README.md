# Movie Recommender System

## 1. Project Objectives & Overview

### 1.1. Business Problem

Ursula, the owner of the DVD store WBSFLIX, wants to take her store online. She is currently operates in a small town near Berlin and is still surviving thanks to a loyal customer base that appreciates the local atmosphere and, more than anything, the personal recommendations from Ursula. 

Ursula is realising that, as her customer base grows, it is difficult for her to find recommendations for each and every customer. With the move to an online store, recommending movies would be almost impossible. She thinks her store could have a design similar to another popular site for movies:

<img width="736" alt="Screenshot 2023-04-21 at 11 28 16" src="https://user-images.githubusercontent.com/120720780/233613907-fcbea30f-d2ba-41ca-b024-ef52b5f08354.png">

Each one of these rows of movies is a different recommendation system: some of them are more personalised than others. 

Ursula has shared her store database with me and working as a freelance Data Scientist my task is to create recommender systems that give users from WBSFLIX relevant content to watch.

### 1.2. Technical Skills 

- Python: Pandas 
- 

## 2. Project Outcome 

### 2.1. Popularity Ranking 

A popularity-based, non-personalised recommender system that takes as an input the ratings and movies datasets and outputs the best movies based on ratings. Using only movies that have had more than 50 ratings. These movies will appear as the top row of the WBSFLIX site.

![Screenshot 2023-04-21 at 11 41 58](https://user-images.githubusercontent.com/120720780/233616552-e016ec5c-8f55-4d8d-9c1b-74696b3c7622.png)

### 2.2. Item-Based Collaborative Filtering

A similarity-based, semi-personalised recommender system that takes a movie as an input and then outputs a list of movies that are “similar” to the one inputted based on rating correlations from the user-item matrix. These movies will appear as the second row of the WBSFLIX site.

![Screenshot 2023-04-21 at 11 42 12](https://user-images.githubusercontent.com/120720780/233616694-199022cf-abe5-4474-91eb-b00b0bd62b42.png)

### 2.3. User-Based Collaborative Filtering

Function that takes the users userId, and a number (n) and outputs the n most recommended movies based on the cosine similarity of other users. Fully personalised recommender system, which will generate the third row on the WBSFLIX site.

![Screenshot 2023-04-21 at 11 42 35](https://user-images.githubusercontent.com/120720780/233616871-9b662f58-b592-40ab-b851-d55ce4db8a47.png)

### 2.4. Creating a ChatBOT Feature

Ursula, asked you whether the similarity-based recommender could be implemented with a more personal touch. Here the user can neter there user ID and the chatbot will recommend a movie based on user-user collaborative filtering. 

![Screenshot 2023-04-21 at 11 45 35](https://user-images.githubusercontent.com/120720780/233617242-922978a8-1dab-4a25-aec6-09dccf03d5d0.png)

