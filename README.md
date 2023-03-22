# Text-prediction
This program implements a statistical trigram language model with NLTK for text prediction based on the Alice in Wonderland corpus.
# IMPLEMENTATION
I used NLTK's probability library to store the probability of each predicted word,
> ConditionalFreqDist()

then the program picks from a weighted random probability to decide which prediction to append to the given phrase.
> random.choices()

The user decides when to stop the program by choosing whether or not to predict the next word.
> "Do you want to generate another word? (type 'y' for yes or 'n' for no): "

# final output of demo:
User input: alice said to the

Prediction: alice said to the table, half hoping she might find another (comma was added for readability)


