# Email Spam Classifier
using Machine Learning models to detect spame Emails
## Data
data is [Apache SpamAssassin’s public dataset](https://spamassassin.apache.org/old/publiccorpus/)

## Techniques
 - Regex
 - nltk
 - IncrementalPCA
 - sklearn

## What i did
 - first was loading the data from multiple files
 - then cleaning the email, with Regex 
    - Convert hh:mm:ss to time
    - Convert URL_address to url
    - Convert Mail_address to email
    - ...
 - doing some eda, getting to know the data
 - creating our vocabulary and Vectorizing it using Tf-if
 - shirinking dataset with PCA
 - training the models
