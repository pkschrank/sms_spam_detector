# sms_spam_detector

# SMS Spam Detector

## Workflow
1. Create the SMS Classification Function
    - Create a features (X) variable from the "text_message" column of the data frame.
    - Create a target (y) variable from the "label" column of the data frame.
    - Split the data using train_text_split function from sklearn with a 33% test size
    - Build a pipeline model to run the tests.
    - Fit the model with training data
2. Load the data to be tested into a data frame.
3. Create the SMS Preduction Function
    - Create a variable to be used with the result of the prediction
    - Conditionally check the result and return a spam or not spam message.
4. Create a Gradio Interface Application
    - Utilizes the SMS prediction function with an input box for test data entry and a text box for the result of the prediction.