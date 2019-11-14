**<u>Convolution</u>**

In Convolution the filter values are multiplied to the entire input image again and again (the amount of such operations depends on the filter size) and the values of the filter are found by the addition of those values.

<u>**Filter / kernel**</u>

Kernels are 2d/3d matrices which store some value which gets multiplied to the input image and then summed to give the output. At the beginning the filter values are random.

**<u>Epoch****</u>**

Epoch is the number of times the model goes through the input data for training. Backpropagation runs after each epoch 

<u>**1x1 convolution**</u>

1x1 convolution can be either used to increase or decrease the number of channels. This operation is normally performed after a Max Pooling Layer. Although it can be used to increase/decrease number of channels, in most cases it is used to decrease the number of channels.                                                                                                                                Eg (100x100x256) | (1x1x256x32) - (100x100x32)

<u>**3x3 convolution**</u>

It is the convolution done with a 3x3 matrix. Normally a 7x7 matrix is not preferred, instead three 3x3 matrices are preferred as the number of parameters in the latter are less.(49 compared to 27)

 <u>**Activation Function**</u>

Just like in neuron the neuron fires gathers all the inputs from the previous neurons and fires only when the summed value of the weights is more than a threshold value activation function works in a similar way. Value = input*weight + bias if greater than threshold then send the signal forward.

 <u>**Feature Maps**</u>

A feature map for a layer is what the filters are recognizing(feature extractor) for the image. The feature map consists of same number of images as the number of filters. As each filter is focusing on a particular feature(horizontal edge, vertical edge) those get highlighted.

 <u>**Receptive Field**</u>

Receptive Field is the amount of pixels a particular layer is able to see. In order to identify objects the receptive field of the model should be equal to the objects number of pixels. Types, - Global and local.

 