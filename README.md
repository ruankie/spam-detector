# Binary Spam Classifier: Natural Language Processing with LSTM in TensorFlow 2

## Project Overview
This model uses a binary classifier to classify a given message as either spam or ham (not spam).
It was created using TensorFlow 2.x and consists of a Long Short Term Memory (LSTM) neural network that is able to capture long-term dependencies in the words that make up a message. This model also uses an embedding layer that encodes words into an abstract 20-dimensional space so that they can be represented as vectors with contextual proximity.

After training this model for 10 epochs on a training data set of 3,715 messages (70% of data set), it produced a validation-accuracy of around 87%.


## References
> This project was based on a project in [this TensorFlow course on Udemy](https://www.udemy.com/course/deep-learning-tensorflow-2/) by the Lazy Programmer.
>The data set used can be found [here](https://lazyprogrammer.me/course_files/spam.csv).