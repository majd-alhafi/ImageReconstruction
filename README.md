# ImageReconstruction
In this repo, I used the [dataset](https://www.kaggle.com/datasets/prondeau/the-car-connection-picture-dataset) that contains about 60K images of cars.
I applied a blur motion filter on images and trained three different autoencoder architectures to remove the blur motion effects: 
- Standard AutoEncoder.
- Variational AutoEncoder.
- Vector-Quantized Variational Autoencoder.

The accuracy is not perfect because those neural networks require so much time to train and Google Colab doesn't give us a high hardware resources.
