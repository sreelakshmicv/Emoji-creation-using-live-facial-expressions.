# EMOJIFY- CREATING EMOJIS USING LIVE FACIAL EXPRESSIONS

![image](https://user-images.githubusercontent.com/98879587/202749437-2987c2f3-b78b-4289-ac46-bf0c920f0ed2.png)

# Introduction

Emojis or avatars are ways to indicate nonverbal cues. These cues have become an essential part of online chatting, product review, brand emotion, and many more. It also lead to increasing data science research dedicated to emoji-driven storytelling.

With advancements in computer vision and deep learning, it is now possible to detect human emotions from images. In this deep learning project, we will classify human facial expressions to filter and map corresponding emojis or avatars.

# Problem statement

We build a deep learning model to classify facial expressions from the images. Then we will map the classified emotion to an emoji or an avatar.


# About the Dataset

The FER2013 dataset ( facial expression recognition) consists of 48*48 pixel grayscale face images. The images are centered and occupy an equal amount of space. This dataset consist of facial emotions of following categories:

0:angry

1:disgust

2:fear

3:happy

4:sad

5:surprise

6:natural

# TOOLKIT

Build a convolution neural network(CNN) architecture and feed the FER2013 dataset to the model so that it can recognize emotion from images. We build the CNN model using the Keras layers in various steps. You can see each layer in the below diagram.

![image](https://user-images.githubusercontent.com/98879587/202766674-8839ed9e-c106-40c6-9eb3-0eed5717aeb4.png)

To build the network we use two dense layers, one flatten layer and four conv2D layers. We are going to use the Softmax equation to generate the model output.

To detect the bounding box of images in the webcam we use the OpenCV’s Haarcascade XML. In the end, we serve these boxes to the trained model for the purpose of classification.

# WORKING PRINCIPLE

The process of FER has three stages. The preprocessing stage consists of preparing the dataset into a form which will work on a generalized algorithm and generate efficient results. In the face detection stage, the face is detected from the images that are captured real time. The emotion classification step consists of implementing the CNN algorithm to classify input image into one of seven classes.

# RESULT

![Uploading Screenshot (428).png…]()


# TOOLS AND LIBRARIES

. Python – 3.x

. Numpy – 1.19.2

. Pandas – 1.2.4

. TensorFlow – 2.4.x

. Emoji – 1.2.0

To install the above modules, run the following command:

pip install numpy pandas tensorflow emoji

# INSTALLATION

To run this code in your local system you have to download this repository using- Git clone

https://github.com/sreelakshmicv/Emoji-creation-using-live-facial-expressions.

Now open the required directories and install python packages required for run the code.Then run the code.

# TRAINING AND EVALUATION

I have used my local system to run this model.

LAPTOP-FOH9E19Q

Intel(R) Core(TM) i3-7020U CPU @ 2.30GHz 2.30 GHz

#FURTHER MODIFICATION

In future you can modify the user interface by creating emojis for both the real time facial emotions as well as the Video/Photo which is already recorded(By uploading those video/photo in the ui and convert to emojis).

We can also try to implement this in keyboards that we use for easier and quicker access of this facial expression detection and emoji generation. We can also try to display a customized emoji of the person’s face.

# AUTHOR

SREELAKSHMI CV  
