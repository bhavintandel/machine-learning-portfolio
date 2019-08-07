# Introduction to Tensorflow for Artificial Intelligence, Machine LEarning, and Deep Learning.

[Link](https://www.coursera.org/learn/introduction-tensorflow) to the course.

This directory contains notebooks and code created in the course.

## Week 1

House Prediction using keras

## Reading Material

#### Conv2D

* Class: tf.keras.layers.Conv2D
* Spatial convolution over images.
* If **use_bias** is True, then bias vector is created and added to the outputs.
* If its a first layer then provide, **input_shape** has to be provided like `input_shape=(128, 128, 3)` for RGB.
* **filters**: to define number of output filters.
* **kernel_size**: integer or tuple/list for height and width of kernel.
* **strides**: strides of convolution.
* **padding**:
  * valid: No padding is done
  * same: we pad the image with -inf and then max pooling is applied
* **data_format**: 
  * channels_first: (batch, channels, height, width)
  * channels_last: (batch, height, width, channels) - Default
* **activation**: eg. linear, relu, tanh, sigmoid  

#### MaxPooling2D

* Max pooling for 2D inputs (images)
* **pool_size**: Single integer or tuple/list for (pool_height, pool_width)
* **strides**: Single integer or tuple/list
* **padding**: valid or same
* **data_format**
* **name**: Name of the layer.

#### 'sigmoid' activation

* Good for binary classification

#### 'softmax' activation

* Good for multi class classification


### Optimizer

* Adam
* Adagrad
* RMSprop
* SGD