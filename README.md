# Autoencoders

Autoencoders are mainly used for dimentionality reduction, large data transfer, and data visualization, I Worked on Convolutional Autoencoders, Denoising Autoencoders and Variational Autoencoders using Tensorflow 2.0.
The main structure of a autoencoder is to reduce the dimentinality of the data by extracting important features from it in a bootleneck and the upsampling the bottlneck to get back the original data (check autoencoder.ipynb), in Denoising autoencoder we pass randon noise into the input data and still try to get the original output (check denoising_autoencoder.ipynb). Variational autoencoders are bit different and it is also called generative model it learns the probablity distribution modeling the data. Its encoder first create a latent space from the input data which is z_mean and z_log_sigma then randomely sample similar points from latent normal distribution then the decoder maps these points to the original input data. 

Reference: https://blog.keras.io/building-autoencoders-in-keras.html 
Please let me know if you any doubt understanding any of the code above.


Isaac.
https://www.linkedin.com/in/isaac-patole223/
