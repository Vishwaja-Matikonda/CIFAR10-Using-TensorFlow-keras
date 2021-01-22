# CIFAR10-Using-TensorFlow-keras

<img width="214" alt="Img classificatiojn" src="https://user-images.githubusercontent.com/40309757/105427194-a0478180-5c72-11eb-89f6-3d827a618370.PNG">

The CIFAR-10 small photo classification problem is a standard dataset used in computer vision and deep learning.Although the dataset is effectively solved, it can be used as the basis for learning and practicing how to develop, evaluate, and use convolutional deep learning neural networks for image classification from scratch.This includes how to develop a robust test harness for estimating the performance of the model, how to explore improvements to the model, and how to save the model and later load it to make predictions on new data.

CIFAR is an acronym that stands for the Canadian Institute For Advanced Research and the CIFAR-10 dataset was developed along with the CIFAR-100 dataset by researchers at the CIFAR institute.The dataset is comprised of 60,000 32×32 pixel color photographs of objects from 10 classes, such as frogs, birds, cats, ships, etc. The class labels and their standard associated integer values are listed below.

These are very small images, much smaller than a typical photograph, and the dataset was intended for computer vision research.CIFAR-10 is a well-understood dataset and widely used for benchmarking computer vision algorithms in the field of machine learning. The problem is “solved.” It is relatively straightforward to achieve 80% classification accuracy. Top performance on the problem is achieved by deep learning convolutional neural networks with a classification accuracy above 90% on the test dataset.

There are 50,000 examples in the training dataset and 10,000 in the test dataset and that images are indeed square with 32×32 pixels and color, with three channels.

     Train: X=(50000, 32, 32, 3), y=(50000, 1)
     Test: X=(10000, 32, 32, 3), y=(10000, 1)

    Train: X=(50000, 32, 32, 3), y=(50000, 1)
    Test: X=(10000, 32, 32, 3), y=(10000, 1)
    
A plot of the first nine images in the dataset is also created. It is clear that the images are indeed very small compared to modern photographs; it can be challenging to see what exactly is represented in some of the images given the extremely low resolution.

This low resolution is likely the cause of the limited performance that top-of-the-line algorithms are able to achieve on the dataset.
