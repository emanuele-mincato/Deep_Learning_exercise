# Deep_Learning_exercises
Implementation of different architectures to solve ML problems:

1) From Pereptron to Deep Neural Networks:
  Write a simple feedforward neural network using Python and NumPy. Start by implementing
  a simple neuron, or perceptron, then define the training algorithm for this simple model.
  The second part consists in defining a simple neural network to perform digits classification.
  
2) Optimize and train Deep Models:
  Explore how to develop a simple Deep Neural Network for a classification problem. I
  explored two common libraries: TensorFlow and Keras. Then I explored how to face a
  well known problem that is common to encounter during the training phase: the Overfitting.
  Finally, I studied how to perform a fair model selection. 

3) Convolutional Neural Networks:
  I explored how to develop a simple Convolutional Neural Network for image classification. 
  I used the Fashion Minst dataset. In the first part, I developed a simple CNN, while in the
  second part I explored the impact of various hyper-parameters in the learning performances.
  
4) Recurrent Neural Networks:
  I explored how to develop a simple Recurrent Neural Network (RNN) for sentiment analysis. 
  As a dataset, I used the IMDB dataset. It contains the text of some reviews and the sentiment
  given by the authors of the reviews (positive review or negative review). The input to the RNN is
  the sequence of words that compose a review. The learning task consists in predicting the sentiment
  of the review. In the first part, I developed a simple RNN, then I explored the differences in 
  terms of computational load, number of parameters, and performances with respect to more advanced
  recurrent models, like LSTM and GRU. Subsequently, I experimented with the bi-directional model 
  to unveil the strengths and the weaknesses of this technique. Finally, I explored how to face 
  overfitting by Dropout.

5) Autoencoders:
  In this homework, I explored how to develop a simple Autoencoder. As a dataset, I used the MNIST dataset. 
  It contains handwritten digits images. In the first part I developed a simple shallow autoencoder,
  then a deep version of it. Next, I experimented with the application of autoencoder on denoising data 
  task (denoising-autoencoder). Finally, I applied this model to sequential domains, considering the IMDB dataset.

6) Variational Autoencoder:
  I explored how to develop a Variational Autoencoder (VAE). As a dataset, I used the MNIST dataset. 
  In developing the VAE I also explored how to develop an ad-hoc layer and a nonstandard training step.
