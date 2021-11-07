# HW 5 Explanation

### Source

I used the following repos to complete this assignment:

- [Reptile](https://keras.io/examples/vision/reptile/)
- [MMoE](https://github.com/drawbridge/keras-mmoe)
- [Avalanche](https://github.com/ContinualAI/avalanche)


### Explanation
Each of these were a different type of learning. In Reptile we did meta learning but on the Cifar10 dataset. The setup was similar to the Omniglot code and some changes were made in the Dataset code in order for it to work. A simple DL model was created and was trained using the Reptile architecture/setup.

In MMoE we attempted to do Multi Task Learning. I originally planned on solving parts of and new things of the Titanic dataset. However I was running into a couple of errors during my test and trial. I ended up using the Toy Census data example to implement and learn about how to do multi task learning. In this they attempt two labels, income of 50,000 and above and marital status.

Lastly we used Avalanche to do continual learning. Avalanche provided many features but I ended up using just the data, model, and metrics. It was quite quick and very easy to setup, similar to some of the other frameworks we have used. However the metrics section was quite a mystery, I wasn't able to display them in a clean manner. The tutorial provided no additional information on how to do so. Other than that it worked really well on the omniglot dataset.

### Demo
Please see the ipynb files and their outputs.