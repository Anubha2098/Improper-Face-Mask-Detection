# Detection of Improperly Worn Face Masks using Deep Learning
Coronavirus disease 2019 has had a pressing impact on people all around the world. Ceasing the spread of this infectious disease is the urgent need of the hour. A vital method of protection against the virus is wearing masks in public areas. Not merely wearing masks, but wearing masks properly can ensure that the respiratory droplets do not get transmitted to other people. 

A deep learning based model is implemented, which can be used to detect people who are not wearing their face masks properly. A convolutional neural network model based on the concept of transfer learning is trained on a self-made dataset of images and implemented with a light-weighted neural network MobileNetV2. OpenCV is used with Caffe framework to detect faces in an input frame which are further forwarded to our trained convolutional neural network for classification. 

The method has been implemented on various input images and classification results have been obtained for the same. The experimental results show that the proposed model achieves a testing accuracy and training accuracy of 93.58% and 92.27% respectively. Optimal results with high confidence scores and correct classification have also been achieved when the proposed model was tested on individual input images.

The model has been trained on a self-made dataset. The dataset contains 250 images of people with 'Proper' face masks, and 250 images of people with 'Improper' face masks. The model is saved as fourth.h5, and loaded for implementation on unseen images to detect is the mask worn by the person is proper or not. 

This project has been done as a part of my Summer Research based in-house Training. The 'Training Report.pdf' file contains detailed information about the implementation of the project.
