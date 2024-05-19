# SMS Spam Detection - NLP Project
The primary goal of this project is to filter and clean SMS messages on a phone by accurately identifying spam messages. This project focuses on developing a machine learning model to detect and classify SMS messages as SPAM or HAM (normal) based on their textual content.
### Exploratory Data Analysis 
- Investigated the presence of NaN values in the dataset.
- Created a count plot to visualize the distribution of SMS labels (Spam vs. Ham).
### Feature Engineering
- Handled the imbalanced dataset issue by applying oversampling techniques.
- Generated new features such as word_count, contains_currency_symbol, and contains_numbers.
### Data Cleaning
- Removed special characters and numbers using regular expressions.
- Converted all SMS messages to lower case.
- Tokenized the SMS messages into words.
- Removed stop words.
- Lemmatized the words to their root forms.
- Joined the lemmatized words back into complete messages.
- Built a corpus of processed messages.
### Model Buliding and Evaluation
Models are evaluated using F1-score
- Random Forest
- Voting Classifier (Decision Tree + Multinomial Naive Bayes)
  
This project successfully demonstrates the use of NLP and machine learning techniques to classify SMS messages as spam or ham.
