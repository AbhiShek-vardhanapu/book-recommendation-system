# Book-Recommendation-System

This notebook demonstrates how to build a collaborative filtering-based recommendation system.

## Table of Contents
1. [What is a Recommendation System?](#what-is-a-recommendation-system)
2. [Types of Recommendation System](#types-of-recommendation-system)
   - [Popularity-based](#popularity-based)
   - [Content-based](#content-based)
   - [Collaborative Filtering](#collaborative-filtering)
   - [Hybrid Filtering](#hybrid-filtering)
3. [Dataset](#dataset)
4. [Requirements](#requirements)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Screenshots](#screenshots)

## What is a Recommendation System?

Whenever we visit a shopping mall to buy a new pair of shoes or clothes, we find a dedicated person who helps us with the kind of products we should buy based on our preferences and makes our job simpler. In simple words, he is a recommendation system. But in this modern world, everything is online, and there is so much content on the internet, there are crores of videos on YouTube, and crores of products on Amazon, which makes it difficult for the user to choose. There comes the recommendation system which makes the user's life simple by recommending the next video to watch or a similar product to buy.

A recommendation system is a piece of code that is intelligent enough to understand the user’s preferences and recommend things based on his/her interest, the goal is to increase profitability. For example, YouTube and Netflix want you to spend more time on their platform, so, they recommend the videos based on the user’s preferences. Amazon wants you to buy products from their website so that they can make more profit.

## Types of Recommendation System

### Popularity-based

Recommending the top products from their website to every user. This method will not consider the user’s interest. For example, the Trending section on YouTube, IMDB top 250 movies.

### Content-based

This is based on the similarity between the products. For example, If a user had watched a movie and liked it, he may like to watch similar movies in the future. This can be based on the genre, actor, actress, or director.

### Collaborative Filtering

This is based on the similarity of users. For example, If person A and B had watched and liked the movie M, next if person A watches the movie Z and likes it, we can recommend the movie Z to person B, since A and B are similar users.

### Hybrid Filtering

This makes use of all or some of the above-mentioned methods to form a hybrid model.

## Dataset

Link to the dataset: [Book Recommendation Dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- surprise
- flask (for web deployment)
- heroku (for web deployment)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/abhishek/book-recommendation-system.git
    ```

2. Change to the project directory:

    ```bash
    cd book-recommendation-system
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Jupyter notebook to build and train the recommendation model:

    ```bash
    jupyter notebook
    ```

2. To deploy the application locally, run:

    ```bash
    flask run
    ```

3. To deploy the application on Heroku:

    - Create a new Heroku app:

        ```bash
        heroku create your-app-name
        ```

    - Push the code to Heroku:

        ```bash
        git push heroku main
        ```

    - Open the deployed app in your browser:

        ```bash
        heroku open
        ```

## Screenshots

![image](https://user-images.githubusercontent.com/94861619/185192233-bf5697e7-18c6-4a48-8513-8ec008a05fc9.png)
![image](https://user-images.githubusercontent.com/94861619/185192354-eb5cceea-fd61-4ef4-bb27-cb0c7924488d.png)
![image](https://user-images.githubusercontent.com/94861619/185192485-8c0725b5-a6bf-4375-b4a3-4fd97bc3aa5e.png)
![image](https://user-images.githubusercontent.com/94861619/185192580-08c59b83-dad9-42ae-8d7f-651026671c31.png)
![image](https://user-images.githubusercontent.com/94861619/185193057-0ce0af03-f29d-4dc3-957d-d6d78d8e7804.png)
![image](https://user-images.githubusercontent.com/94861619/185193122-9eb75cba-8bc0-461c-bd07-b06c64fce28f.png)
![image](https://user-images.githubusercontent.com/94861619/185193220-92639711-2af8-4517-a8a9-10535fd2a234.png)
![image](https://user-images.githubusercontent.com/94861619/185193295-124ff4f3-c24b-4124-977d-6d44eb3edccc.png)
