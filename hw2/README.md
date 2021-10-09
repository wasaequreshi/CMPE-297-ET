# HW 2 Explanation

### Source

I used the following links to complete this assignment:

- [Keras Perceiver ](https://keras.io/examples/vision/perceiver_image_classification/)
- [Perceiver IO Example](https://github.com/2796gaurav/code_examples/blob/main/Perceiver/Perceiver_optical_flow.ipynb)

Most of the implementation was copy and paste but I had to move things around to make it work in one ipynb file. This in addition gave me exposure to understand the code as I tried to copy and paste to make it work. 

### Part a

This is an implementation of Perciever using Keras. The `cifar100` dataset was used with the Keras model. Inital data preperation is done to split train and test data. Parameters for the model then described. I changed the epochs to 1 because each epoch takes about 8 mins to execute, making the execution time 6 hours. The colab would disconnect and wouldn't finish in an adequete amount of time. Some data augmentations are applied such as normalize, resizing, flipping and zooming. A feed forward network (FFN) is then created which will be used by the cross-attention module and transformer module. This is used for approximation output for each of the respective module. Patches are implemented as well to extract data from the images we pass to the perceiver model. Finally the perceiver model aggregates the modules and patches in addition to a couple layers and is executed. The accuracy starts of similar to the authors execution output (5%, authors had 3%). However due to limited resources we stopped after the first epoch.


### Part b

Now we are using perceiver io for optical flow. This is a cool project, between two images, it tells you which objects are affected and moving in. There are a couple of dependencies such as haiku (for familiar object orientation) and einops (deep learning operations). The model is similarly constructed to what we did in part a. A function is implemented to compute the folow of images which is used by the perceiver to figure out what direction or flow the image is going from one frame to another. There is an existing perceiver model that is used (pickled) for optical flow and applied on the two images. There is no accuracy but you can visualize and see the areas of the optical flow of the two frames. If you open the two images on your computer and look between the two images, you'll see that the optical flow model does a accurate job of showing what objects in the images are moving.

### Demo

Please take a look at the ipynb files. They have results and visualizations.