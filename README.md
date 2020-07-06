# House-Price-prediction 
In this project, we solve this regression model using Keras and Tensorflow. We will be using neural network to solve this problem. 

TensorFlow is the premier open-source deep learning framework developed and maintained by Google. Although using TensorFlow directly can be challenging, the modern tf.keras API beings the simplicity and ease of use of Keras to the TensorFlow project.

This integration is commonly referred to as the tf.keras interface or API (“tf” is short for “TensorFlow“) to distinguish it from the so-called standalone Keras open source project.
Standalone Keras :- The standalone open source project that supports TensorFlow, Theano and CNTK backends.
tf.keras :- The Keras API integrated into TensorFlow 2.
Using tf.keras allows you to design, fit, evaluate, and use deep learning models to make predictions in just a few lines of code. It makes common deep learning tasks, such as classification and regression predictive modeling, accessible to get things done.

We have used the dataset :- 'data.csv'

The neural network model is a Sequence-type. It uses dense layers and 'relu'(Rectified Linear Units) as activation function.
During training, we use a 'EarlyStopping' callback.
The number of epochs is a hyperparameter that defines the number times that the learning algorithm will work through the entire training dataset.
One epoch means that each sample in the training dataset has had an opportunity to update the internal model parameters. 
Too many epochs can lead to overfitting of the training dataset, whereas too few may result in an underfit model. Early stopping is a method that allows you to specify an arbitrary large number of training epochs and stop training once the model performance stops improving on a hold out validation dataset.

In this project, we've created,trained and evaluated a neural network model that after training will be able to accurately predict price of a house if provided with some information like the age of the house, location and so on.
