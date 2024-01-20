# Movie Sentiment Analysis

![Project Logo/Image](https://github.com/omaarelsherif/Movie-Reviews-Sentiment-Analysis-Using-Machine-Learning/blob/main/Images/Movies_Header.jpg?raw=true)
## ➲Overview

This repository contains the code and resources for performing sentiment analysis on movie reviews using a machine learning approach. Sentiment analysis involves determining the sentiment or emotion expressed in a piece of text, and in this project, we focus on analyzing sentiments in movie reviews.

## ➲Prerqusites

This is list of required packages and modules for the project to be installed :

- Python 3.x

- Pandas

- Numpy

- BeautifulSoup

- Scikit-learn

- NLTK

Install all required packages :
```bash
!pip install -r required_libraries.txt
```
## ➲The Dataset

Human activites dataset contain about 50000 record which is a sample of movie's review
and a target column "sentiment" which describe the sentiment of the viewer about the movie either it is positove or negative.

**Dataset features and target:**

![Project Logo/Image](https://github.com/omaarelsherif/Movie-Reviews-Sentiment-Analysis-Using-Machine-Learning/blob/main/Images/Dataset_Columns.png?raw=true)

**Dataset head:**

![Project Logo/Image](https://github.com/omaarelsherif/Movie-Reviews-Sentiment-Analysis-Using-Machine-Learning/blob/main/Images/Dataset_Head.png?raw=true)

## ➲Coding Section

In this part we will see the project code divided to sections as follows:
<br>

- Section 1 | Data Preprocessing :<br>
In this section we aim to do some operations on the dataset before training the model on it,
<br>processes like :
  - Loading the dataset
  - Encoding ouput to binary (Positive : 1 , Negative : 0) 
  - Data cleaning : Remove HTML tags
  - Data cleaning : Remove special characters
  - Data cleaning : Convert everything to lowercase
  - Data cleaning : Remove stopwords
  - Data cleaning : Stemming<br><br>

- Section 2 | Model Creation :<br>
The dataset is ready for training, so we create a Naive Bayes model using scikit-learn and then fit it to the data.<br>

- Section 3 | Model Evaluation :<br>
Finally we evaluate the model by getting accuracy, classification report and confusion matrix.


## ➲Installation


1. **Clone the Repository:**
   ```bash
   git clone https://github.com/rishika_shrimal2107/movie_sentiment_analysis_.git
   ```

   2. **Run the code from cmd:**
   ```bash
   python movie_reviews_sentiment_analysis_.py
   ```

   ## ➲Contact

- E-mail   : [shrimalrishika@gmail.com](mailto:shrimalrishika@gmail.com)
- LinkedIn : https://www.linkedin.com/in/rishika-shrimal-7577a7221/
   

