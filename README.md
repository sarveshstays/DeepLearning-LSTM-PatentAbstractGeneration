# DeepLearning-LSTM-PatentAbstractGeneration
Build and use a recurrent neural network in Keras to write patent abstracts

# Patent Abstract Case Study

we input a sequence of words and train the model to predict the very next word.

When we go to write a new patent, we pass in a starting sequence of words, make a prediction for the next word, update the input sequence, make another prediction, add the word to the sequence and continue for however many words we want to generate.

The steps of the approach are outlined below:

Convert abstracts from list of strings into list of lists of integers (sequences)
Create feature and labels from sequences
Build LSTM model with Embedding, LSTM, and Dense layers
Load in pre-trained embeddings
Train model to predict next work in sequence
Make predictions by passing in starting sequence

