# Cyberbullying-Detection
In this project , i aim to build a model that can detect Cyberbullying on twitter.<br>
As we know With rise of social media coupled with the Covid-19 pandemic, cyberbullying has reached all time highs. We can combat this by creating models to automatically flag potentially harmful tweets as well as break down the patterns of hatred.<br>
# Dataset
The dataset used in this project is the [Cyberbullying Classification](https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification) available on Kaggle.<br>
The dataset consists of text inpupts labeled with six classes :
* Age 
* Ethnicity
* Gender
* Religion
* Other type of cyberbullying
* Not cyberbullying

# Preprocessing 

I have performed several preprocessing techniques on the dataset to improve the quality of the input data, including:
* Text cleaning : removing special characters and punctuation marks.
* Tokenization : splitting the text into individual words or tokens.
* Stop word removal: removing common words that are not useful for the analysis.
* Lemmatization: reducing words to their base form.
* Embeddings : the representation is a vector that encodes the meaning of the word in such a way that words that are closer in the vector space are expected to be similar in meaning.

# Models 
I have experimented with multiple machine learning and deep learning models for this task, including:
* Logistic Regression
* Random Forest Classifier
* LSTM (Long Short Term Memory)
