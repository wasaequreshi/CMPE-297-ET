# HW 1 Explanation

### Source

I used the following repos to complete this assignment:

- [Pytorch simclr ](https://github.com/thunderInfy/simclr)
- [TensorFlow simclr](https://github.com/sayakpaul/SimCLR-in-TensorFlow-2)

Most of the implementation was copy and paste but I had to move things around to make it work in one ipynb file. This in addition gave me exposure to understand the code as I tried to copy and paste to make it work. 

### Part a

This is an implementation using Pytorch. This uses the milli_imagenet dataset, a custom small version with 1250 training and 250 test records. The pretrained model used is a resnet18 model with a couplpe linear layers and relu functions. A couple of image augmentations are done such as color distortion  and normalization. Then the training proceeds for the (model + simclr). I needed to use a smaller batch size, 50, as the program would not finish. I would run into some memory issues. The accuracy was around 66%.

### Part b

This is an implementation using Tensorflow. This used a subset of the ImageNet dataset, 1250 training and 250 testing. This had the same augmentations applied as we did in PyTorch. And the pretrained model was identical as well. Different linearities and projections were used and we were eventually able to get a 64% accuracy.

### Demo

Please take a look at the ipynb files. They have results and visualizations.