# Spam-Detection-Chatbot
Fine Tuning a Pre Trained LLM for spam sms detection

LLM used - DistilBert

I wanted to train the LLM to detect spam messages with very high accuracy.
To do this I made use of a spam.csv file that I found on Kaggle which contained around 5700 messages and identified them as either ham or spam.


I have uploaded this data set in the drive folder for reference.

I then split the columns into separate lists, converted the ham or spam into 0s or 1s (1 for spam) and then tokenized the input texts using the DistilBert tokenizer after which I split the data randomly (80/20) into train and test data.

I then set hyperparameters for training and performed training on the data…

I checked the results to find that the model perfectly predicts the testing data with absolutely no errors.

I then tried the model out on my own inputs and it worked really well.

Then I proceeded to convert the model into a GUI using Gradio which was very easy using the code from assignment 4.

After which i played around with the GUI with different inputs
