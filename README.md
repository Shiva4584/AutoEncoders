# AutoEncoders
This repo consists of different types of autoencoders for data compression.
<h1> Building a simple AutoEncoder </h1>
<h3>What are autoencoders?</h3>

![download](https://user-images.githubusercontent.com/68855488/179143551-396f1b92-0ab2-465e-b873-52ec0665cce5.png)

"Autoencoding" is a data compression algorithm where the compression and decompression functions are :
> * Autoencoders are data-specific, which means that they will only be able to compress data similar to what they have been trained on.
> * Autoencoders are lossy, which means that the decompressed outputs will be degraded compared to the original inputs.
> * Autoencoders are learned automatically from data examples, which is a useful property: it means that it is easy to train specialized instances of the algorithm that will perform well on a specific type of input. 

<center><h4> Original vs Reconstructed </h4></center>

![download](https://user-images.githubusercontent.com/68855488/179143810-f11e6142-9f87-45a3-9f51-f76e2b20218a.png)

<hr.

<h1>Deep AutoEncoder</h1>
We do not have to limit ourselves to a single layer as encoder or decoder, we could instead use a stack of layers.

<h4> Original vs Reconstructed </h4>

![download](https://user-images.githubusercontent.com/68855488/179144032-72404a09-48fd-4145-9056-06eb523b272f.png)

<hr>

<h1>Convolutional AutoEncoder</h1>
Since our inputs are images, it makes sense to use convolutional neural networks (convnets) as encoders and decoders. In practical settings, autoencoders applied to images are always convolutional autoencoders --they simply perform much better.

<h4> Original vs Reconstructed </h4>

![download](https://user-images.githubusercontent.com/68855488/179144361-b14395e6-10d4-407d-8d98-3b24f0c0f140.png)

<hr>
