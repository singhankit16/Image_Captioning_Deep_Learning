# Image_Captioning_Deep_Learning(COCO Dataset)

### Abstract
Image Captioning refers to the process of generating textual description from an image – based on the objects and actions in the image. Image captioning is interesting to us because the problem setting requires both an understanding of what features (or pixel context) represent which objects, and the creation of a semantic construction “grounded” to those objects. The task of image captioning is divided into two modules – Image based modules and language-based module. For Image based module, we rely on Convolutional Neural Network model and for the languages-based module, we rely on a Recurrent Neural Network.

### Introduction
Automatically generating textual description from an artificial system is the task of image captioning. When given an image, the model describes in English what is in the image. To achieve this, our model is comprised of an encoder which is a CNN and a decoder which is an RNN. The CNN encoder is given images for a classification task and its output is fed into the RNN decoder which outputs English sentences.  Usually, a pretrained CNN extracts the features from our input image. The feature vector is linearly transformed to have the same dimension as the input dimension of the RNN/LSTM network. This network is trained as a language model on our feature vector. For training our LSTM model, we predefine our label and target text
![image](https://github.com/singhankit16/Image_Captioning_Deep_Learning/blob/master/Image.PNG)

### Dataset
We use the Microsoft Common Objects in Context (MS COCO) dataset for this project. It is a large-scale dataset for scene understanding. The dataset is commonly used to train and benchmark object detection, segmentation, and captioning algorithms. COCO enables data-intensive deep neural networks to learn the mapping from images to sentences, given a comparatively large dataset of images with multiple human-label descriptions of said images

### Results
![Results](https://github.com/singhankit16/Image_Captioning_Deep_Learning/blob/master/Results.PNG)
