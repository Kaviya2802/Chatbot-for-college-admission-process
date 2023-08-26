# Chatbot-for-college-admission-process
In this Python web-based project with source code, we are going to build a chatbot using deep learning and flask techniques. The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. We use a special artificial neural network (ANN) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.

The project requires you to have good knowledge of Python, Keras, and Natural language processing (NLTK). Along with them, we will use some helping modules which you can download using the python-pip command.
**The file structure**
data.json – The data file which has predefined patterns and responses.
trainning.py – In this Python file, we wrote a script to build the model and train our chatbot.
Texts.pkl – This is a pickle file in which we store the words Python object using Nltk that contains a list of our vocabulary.
Labels.pkl – The classes pickle file contains the list of categories(Labels).
model.h5 – This is the trained model that contains information about the model and has weights of the neurons.
app.py – This is the flask Python script in which we implemented web-based GUI for our chatbot. Users can easily interact with the bot.

Here are the 5 steps to create a chatbot in Flask 

Import and load the data file
Preprocess data
split the data into training and test
Build the ANN model using keras
Predict the outcomes
Deploy the model in the Flask app

