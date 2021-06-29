# HUMAN-FACIAL-EXPRESSION-RECOGNITION

### INTRODUCTION :

Facial Expressions plays an important role in interpersonal communication. Facial expression is a non verbal scientific gesture which gets expressed in our face as per our emotions. Automatic recognition of facial expression plays an important role in artificial intelligence and robotics and thus it is a need of the generation. 

Human  facial expressions convey a lot of information visually rather than articulately. Facial expression recognition plays a crucial role in the area of human-machine interaction. Automatic facial expression recognition system has many applications including, but not limited to, human behavior understanding, detection of mental disorders, and synthetic human expressions. Recognition of facial expression by computer with high recognition rate is still a challenging task

The objective of this project is to develop an  Automatic Facial Expression Recognition System which can take human facial images containing some expression as input and recognize and classify it into seven different expression  classes  such as : Anger, Disgust , Fear, Happy, Sad, Surprise and Neutral.
     
    
Convolutional Neural Networks achieve better accuracy with big data. However, there are no publicly available datasets with sufficient data for facial expression recognition with deep architectures. Therefore, to tackle the problem, we apply some pre-processing techniques to extract only expression specific features from a face image and explore the presentation order of the samples during training. We have used an open source data set FER 13 from Kaggle and built a CNN to detect emotions.  The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

### ARCHITECTURE OF CONVOLUTION NEURAL NETWORK :

![image](https://user-images.githubusercontent.com/85671826/123841528-4b005200-d92d-11eb-876c-5c71c8b8ab2e.png)

**1. Convolutional Layer**
This layer is the first layer that is used to extract the various features from the input images. In this layer, the mathematical operation of convolution is performed between the input image and a filter of a particular size MxM. By sliding the filter over the input image, the dot product is taken between the filter and the parts of the input image with respect to the size of the filter (MxM).The output is termed as the Feature map which gives us information about the image such as the corners and edges. Later, this feature map is fed to other layers to learn several other features of the input image.

**2. Pooling Layer**
Pooling layer plays an important role in pre-processing of an image. Pooling layer reduces the number of parameters when the images are too large. Pooling is "downscaling" of the image obtained from the previous layers. It can be compared to shrinking an image to reduce its pixel density. Spatial pooling is also called downsampling or subsampling, which reduces the dimensionality of each map but retains the important information.


**3. Fully Connected Layer**
The fully connected layer is a layer in which the input from the other layers will be flattened into a vector and sent. It will transform the output into the desired number of classes by the network.

 ### CONCLUSION :
 
The proposed system provides an alternative scheme for human emotion recognition from facial  images, using convolutional neural networks , which is a specialized type of neural network model designed for working with two-dimensional image data, although they can be used with one-dimensional and three-dimensional data.It takes an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other.

Convolutional neural network is composed of multiple building blocks, such as convolution layers, pooling layers, and fully connected layers, and is designed to automatically and adaptively learn spatial hierarchies of features through a back propagation algorithm.

Convolutional Neural Networks are a type of Deep Learning Algorithm that take the image as an input and learns the various features of the image through filters. This allows them to learn the important objects present in the image, allowing them to discern one image from the other. For example, the convolutional network will learn the specific features of cats that differentiate it from the dogs so that when we provide input of cats and dogs, it can easily differentiate between the two. One important feature of Convolutional Neural Network that sets it apart from other Machine Learning algorithms is its ability to pre-process the data by itself. Thus, you may not spend a lot of resources in data pre-processing.


