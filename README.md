# sms_spam_detector
Refactoring code from an SMS text classification solution into a function that constructs a linear Support Vector Classification (SVC) model

## Description

This project refactors code from an SMS text classification solution into a function that constructs a linear Support Vector Classification (SVC) model, trains it and creates a Gradio app to host the application. App users will be able to test text messages and recieve feedback to from the app to indicate whether a text is classified as spam or not.


### Skills Demonstrated

The primary skills demonstrated include the ability to:
* Create SMS classification and prediction functions
* Create Gradio interface applications


### Dependencies

Python Libraries and Functions
* pandas
* train_test_split (from sklearn.model_selection)
* Pipeline (from sklearn.pipeline)
* TfidfVectorizer (from sklearn.feature_extraction.text)
* LinearSVC (from sklearn.svm)



## Contributor

Jamie Bond | jamie.bond@pathkonkat.com | [Connect on Linkedin](https://linkedin.com/in/jamielbond)

## Acknowledgments

Adapted from instructions starter files provided by [The Artificial Intelligence Boot Camp at UNC Charlotte](https://bootcamp.charlotte.edu/artificial-intelligence/), including:
* gradio_sms_text_classifcation.ipynb starter code