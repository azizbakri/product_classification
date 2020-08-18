# Product_classification

## Project Description

This project consists of classifying products using their text description into different categories. The categories are classes in the ETIM or ECLASS classification standards.

## Project Structure

The project is structured into 2 parts:
First part: Natural Language Processing: The preprocessing of the text and the vectorization of the words.
Second part: Deep Learning classification: Different deep learning models take the vectorized results from the previous step and classify it into a certain category. 

## Code

The code is structured into 3 jupyter notebook:

* Preprocessing: The description text is cleaned here. (duplicated rows and words are removed, ...)
* Vectorization: The cleaned description text is embedded into vectors using the Word2Ved algorithm. 
* Models: The classification of the vectors (descriptions) into a the wanted categories.


**note:** The cross validation notebook is not finished (will be updated in the future) and the Machine learning classification notebook contains another solution for this problem using normal machine learning algorithms (no deep learning) and a previous NLP approach for vectorization (TFIDF). 
