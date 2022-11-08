# Neural-Network-from-Scratch

Deep learning is a technique in which you let the neural network figure out by itself which features are important instead of applying feature engineering techniques. This means that, with deep learning, you can bypass the feature engineering process.

Not having to deal with feature engineering is good because the process gets harder as the datasets become more complex. For example, how would you extract the data to predict the mood of a person given a picture of her face? With neural networks, you don’t need to worry about it because the networks can learn the features by themselves. In the next sections, you’ll dive deep into neural networks to better understand how they work.

A neural network is a system that learns how to make predictions by following these steps:

    1. Taking the input data
    2. Making a prediction
    3. Comparing the prediction to the desired output
    4. Adjusting its internal state to predict correctly the next time

Vectors, layers, and linear regression are some of the building blocks of neural networks. The data is stored as vectors, and with Python you store these vectors in arrays. Each layer transforms the data that comes from the previous layer. You can think of each layer as a feature engineering step, because each layer extracts some representation of the data that came previously.

In this project we first build a neural network and then test it on both classfication and regression dataset. For classification task iris dataset is used and for regression task diabetes dataset is used.
