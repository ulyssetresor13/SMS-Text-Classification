# Neural Network SMS Text Classifier

In this challenge, created a machine learning model that will classify SMS messages as either "ham" or "spam". A "ham" message is a normal message sent by a friend. A "spam" message is an advertisement or a message sent by a company.

Created a function called predict_message that takes a message string as an argument and returns a list. The first element in the list is a number between zero and one that indicates the likeliness of "ham" (0) or "spam" (1). The second element in the list is the word "ham" or "spam". Using SMS Spam Collection dataset grouped into train data and test data achieved an accuracy of 98 %.

## Framework & Tools used
- Keras
+ NLTK
* Model: LSTM
+ Optimizer : RMSprop
- Loss: binary_crossentropy
