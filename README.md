# Description
This deep convolutional autoencoder removes Gaussian noise from CIFAR-10 images using an architecture inspired by ["Image Denoising with Deep Convolutional Neural Networks."](https://web.stanford.edu/class/cs331b/2016/projects/zhao.pdf) What makes this model unique is the inclusion of residual modules (referred to in the paper as Direct Symmetric Connections). Modulated by a "gating factor," these connections help propagate image features of various scales from the encoder to the decoder, thus allowing for a more accurate estimation of the original, noise-free image.

# Example Results
The format of these result images is (Original, Noisy, Reconstruction), where Reconstruction is the model's response to the Noisy input. Note that the images displayed are resized from CIFAR-10's 32x32 resolution to an easier-to-view 256x256 using bicubic interpolation.

![Result 1](https://user-images.githubusercontent.com/15223179/64203817-2b8b6180-ce49-11e9-8afe-ba226b7b6118.png)

![Result 2](https://user-images.githubusercontent.com/15223179/64203821-2e865200-ce49-11e9-912b-3a819c98e14b.png)

![Result 3](https://user-images.githubusercontent.com/15223179/64203826-30501580-ce49-11e9-9eae-36bfec19dd9d.png)

![Result 4](https://user-images.githubusercontent.com/15223179/64203831-334b0600-ce49-11e9-9a67-b5e6a96ff971.png)

![Result 5](https://user-images.githubusercontent.com/15223179/64203833-3514c980-ce49-11e9-8269-7974aebea70e.png)