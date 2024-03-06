# NLP Essentials Project: Sentiment Analysis on Movie Reviews

## Project Scenario

In a recent market research by IBM, almost one-third of IT professionals surveyed globally say their business is using Artificial Intelligence (AI). The survey reported almost half of businesses today are now using applications powered by natural language processing (NLP).

NLP, specifically 'Sentiment Analysis', can provide a key business advantage by abstracting from unstructured text data the negative or positive attitude of the writer/author. This crucial insight can help turn web data into market intelligence for the business.

A request has been received from the web development department to add 'Sentiment Analysis' feature to a movie reviews page.

The insights from the sentiment analysis will be used to promote more popular movies.

In this project, you are tasked to create a prototype NLP project that is capable of 'Sentiment Analysis' from movie reviews.

## Tasks

### 1. Problem Scoping
Define the problem statement using the 4Ws (Who, What, Where, Why) problem canvas from the project scenario.

### 2. Data Acquisition and Data Exploration
#### 2.1. Importing Various Modules
Import necessary libraries for data preprocessing and analysis.

#### 2.2. Preparing the Data
- Preprocess text
- Perform image pre-processing and data augmentation
- Split data into train, validate, and test datasets
- Perform Feature Extraction Using TF-IDF

### 3. Modelling
Create the model based on Neural Network.

### Task 2: Data Acquisition and Data Exploration
#### Task 2.1: Importing Various Modules - Data Cleansing
Import relevant NLTK libraries for text processing.

#### Task 2.2: Data Exploration
- Check for missing values
- Basic Statistics
- Tokenization and Text Length Analysis
- Word Frequency Analysis
- Sentiment Distribution Visualization

#### Task 2.2.1: Importing Various Modules - Add More Stop Words to NLTK
Add additional stop words to NLTK's stopwords list.

#### Task 2.2.2: Process Text - Tokenize, Remove Punctuation, Lemmatize
Implement functions for text cleaning, lemmatization, and processing.

### Part 2: Perform AI Natural Language Inference
#### Task 2.2.3: Split Dataset Into Train Test Sets
Split the dataset into training and testing sets.

#### Task 2.2.4: Feature Extraction Using TF-IDF
Perform normalization of bag of words using TF-IDF.

### Task 5: Create Model Using Neural Networks
Create and train a suitable neural network model for sentiment analysis.

### Task 6: Test For Unseen Text
Use the trained model to make predictions on totally unseen text.

### Task 7: Apply Cosine Similarity to Find Similar Texts
Find the top most similar sentences from the training dataset based on given unseen positive and negative text.

## Conclusion
In this project, we successfully implemented sentiment analysis on movie reviews using NLP techniques. The model achieved an accuracy of XX% on the test dataset.

## Dependencies
- pandas
- numpy
- nltk
- tensorflow
- matplotlib
- seaborn
- scikit-learn

## How to Use
1. Clone the repository.
2. Install the required dependencies using pip install -r requirements.txt.
3. Execute the Jupyter Notebook to run the code.
