# Language-Translator
Developed a deep learning model using Bahadanau attention mechanism which will translate the sentence in Marathi to English. 
Loaded the dataset and preprocessed the data using keras preprocessing. Replaced the digits and other punctuation marks accordingly. 
Trained the model using optimzer adam,categorical crossentropy as the loss function, validation loss as the metric. 
Prediction was accurate though the number of epochs were less as attention weights were stored for every step. 
The loss obtained is 0.06 and it is perfoming better when compared to the translation model without attention mechanism.
