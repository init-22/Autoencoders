# Autoencoders

Autoencoders are mainly used for dimensionality reduction, big data transfer and data visualization. I worked on Convolutional Autoencoders, Denoising Autoencoders and Variational Autoencoders using Tensorflow 2.0.

The main aim of a autoencoder is to reduce the dimensionality of the data by extracting important features from it in a bootleneck and then  getting back the original data (check convolutional_autoencoder.ipynb).

In Denoising autoencoder we pass randon noise into the input data and still try to get the original output (check denoising_autoencoder.ipynb).


Variational autoencoders are bit different and it is also called generative model, it learns the probablity distribution modeling the data. Its encoder first create a latent space from the input data which is z_mean and z_log_sigma. Then, randomly sample similar points from latent normal distribution then the decoder maps these points to the original input data. KL divergence is used to achieve this. (check variational_autoencoder.ipynb).


Reference:

Keras Blog: https://blog.keras.io/building-autoencoders-in-keras.html

Variational Autoencoder by Prof. Ali Ghodsi: https://www.youtube.com/watch?v=uaaqyVS9-rM&t=2120s
