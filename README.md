# ImageDetector
<p align="center">
<a href = "https://github.com/yilmazvolkan/ImageDetector"><img 
<img src="https://github.com/yilmazvolkan/ImageDetector/blob/master/drawable/logo.png" width="470" height="150"></a>
</p>

## :flashlight: Before You Go

You need to install Keras library on Python. You can reach this library clicking on this [link](https://github.com/keras-team/keras).

Moreover, since the dataset is huge, you need to download it from [here](https://github.com/keras-team/keras).

## :tophat: Summary

Convolutional Neural Networks is gaining interest rapidly. It helps to analyze images by classfiying them according to their pixels.


In CNN, we take filter which is determined before and apply into image. Therefore, we create feature map. We reduce the size of the image by using filter and we gain speed to process. However, we are lossing some information about the image but our goal is detect the features from the image. We do not examine every single pixel, we just need to look at features. Therefore, we can get rid of unnecessary things. Actually, we can create different feature maps since we use different filters. That's another way to preserver some information about the image.


MaxPooling hepls CNN to be more flexible about detecting features since most of the time features are rotated. It also reduces the size and it is good for processing. Flattening is the process that takes pooled feature map and converts into one column array for input layer of ANN. Moreover, when we gain some results with probabilities, most of the time it does not add up to 1. Softmax solves this problem by adjusting them into 0-1 scala.


## :blue_book: Readings

You can reach more information about convolutional networks by clicking on this [link](https://arxiv.org/pdf/1409.1556v6.pdf).

Another good article about Cross-Entropy Loss is on this [link](https://rdipietro.github.io/friendly-intro-to-cross-entropy-loss/).

Another good article about MaxPooling is on this [link](http://ais.uni-bonn.de/papers/icann2010_maxpool.pdf).

## :beers: Contributers


<p align="left">
<a href = "https://github.com/yilmazvolkan"><img 
<img src="https://avatars2.githubusercontent.com/u/28186366?s=400&v=4" width="120" height="120"></a>
</p>
