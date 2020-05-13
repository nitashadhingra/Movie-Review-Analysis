# Movie-Review-Analysis

- Keras is a high-level neural networks API. 
- Used Keras to build and train a neural network to perform sentiment analysis.
- Keras is running on top of Tensorflow.
- Used the neural network to analyze text for sentiment.

## Input data
To train a neural network, training data used is the IMDB movie reviews sentiment classification.

## Creating neural networks with keras
- An embedding layer, which is crucial to neural networks that processes words is added which allows words with similar meanings to be treated alike.  
- Next three layers added to the model are dense layers. Each layer contains n nodes or neurons, and each neuron receives input from every neuron in the previous layer, hence the layers are said to be fully connected. It is these layers that permit a neural network to learn from input data by iteratively guessing at the output, checking the results, and fine-tuning the connections to produce better results. 
- The final dense layer contains just one neuron because the ultimate goal of the network is to predict one output — namely, a sentiment score from 0.0 to 1.0.

## Overfitting
If the model is trained for any longer than required it tends to overfit. 
Overfitting, or high variance, is caused when the model fits the available data but does not generalize well to predict new data.
Two main options to address the issue of overfitting:
1) Reduce the number of features
2) Regularization (Works well when we have a lot of slightly useful features)

## Check for overfitting
Compared training loss to validation loss as training proceeds. For a given epoch, training loss, much greater than validation loss, can be evidence of overfitting. 

