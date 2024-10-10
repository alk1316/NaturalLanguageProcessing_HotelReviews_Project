<a name="readme-top"></a>
<br />
<div align="center">

  # BrainStation Project
### Natural language processing (NLP) Hotel Reviews

  </a>


</div>

## Project Overview

The goal of this project is to predict customer satisfaction based on their reviews.

To achieve this, we will use a dataset containing both positive and negative reviews. By applying NLP models, we aim to predict customer satisfaction based on their feedback.

- Link to the dataset used: https://drive.google.com/file/d/1peaWkWDkbDPbDNWZrEejuSGx3lZo6NfJ/view?usp=sharing
- Link to the project [Jupyter Notebook](NLP_With_Hotel_Review.ipynb)


# Project Workflow

The steps followed during the process were as follows:

1. **Loading the Dataset and Required Libraries**: The data and necessary libraries were imported for analysis.

2. **Exploratory Data Analysis (EDA)**: The dataset was examined to understand its structure, distributions, and key features.

3. **Preprocessing**:
   - **Text Cleaning**: Unnecessary characters were removed, and the text was standardized.
   - **Tokenization**: Text was split into individual words.
   - **Applying Stopwords and Lemmatization**: Common, non-informative words were removed, and words were reduced to their base form.

4. **Train and Test Data Split**: The data was split into training and testing sets for model evaluation.

5. **Applying CountVectorizer**: The text was transformed into a word count matrix for use in the models.

6. **Modeling with 2 Models**:
   - **Logistic Regression**: Used to predict customer satisfaction and identify the most predictive reviews (positive and negative).
   - **Decision Tree**: A pipeline was implemented with PCA to improve model performance.

7. **Hyperparameter Tuning**: The model parameters were fine-tuned to enhance performance.

8. **Confusion Matrix**: Generated to evaluate the accuracy of the models' predictions.

9. **Evaluating Both Models**: The results from Logistic Regression and Decision Tree models were compared.

10. **Conclusions**: The results were analyzed, and conclusions were drawn about the performance and effectiveness of the applied models.





