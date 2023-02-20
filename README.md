# GAN
 Generative Adversarial Network (GAN)
#
 A generative adversarial network (GAN) is a type of deep learning network that can generate data with similar characteristics as the input real data.
# A GAN consists of two networks that train together:
####    1 Generator — Given a vector of random values (latent inputs) as input, this network generates data with the same structure as the training data.

####    2 Discriminator — Given batches of data containing observations from both the training data, and generated data from the generator, this network attempts to classify the observations as "real" or "generated".

This diagram illustrates the generator network of a GAN generating images from vectors of random inputs.
![TrainGenerativeAdversarialNetworkGANExample_01](https://user-images.githubusercontent.com/51045212/220172258-1f0bd88d-31ca-47b5-9e4a-f357d25917b2.png)

This diagram illustrates the structure of a GAN.
![TrainGenerativeAdversarialNetworkGANExample_02](https://user-images.githubusercontent.com/51045212/220172367-c786acba-6b26-41e9-8943-9e495c695d13.png)


To train a GAN, train both networks simultaneously to maximize the performance of both:

    Train the generator to generate data that "fools" the discriminator.

    Train the discriminator to distinguish between real and generated data.
 
 Reference:
 mathworks: https://de.mathworks.com/help/deeplearning/ug/train-generative-adversarial-network.html?searchHighlight=Train%20Generative%20Adversarial%20Network%20%28GAN&s_tid=srchtitle_Train%20Generative%20Adversarial%20Network%20%2528GAN_1
 
 tensorflow:https://www.tensorflow.org/tutorials/generative/dcgan
