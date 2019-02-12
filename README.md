# PyTorch to Keras

### Transfer pytorch model weights to matched keras model 

In this repo I will show you how to transfer weights from pytorch to keras.
I decided to create this repo since I couldn't find any simple solution (that works) for transfering weights between this two APIs.

In the current version it's possible to transfer weights only from pytorch to keras.

Supported layers:
* Conv2D
* Dense
* BatchNormalization
