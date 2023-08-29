#          <h3 align="center">COVID-19-Detection using chest X-RAY images</h3>


###         1.Introduction and Abstract

In this [project](Covid_19.ipynb), we performed the binary classification of chest x-ray images using Neural Network Model to find the patient is covid-19 positive or normal. Most of the Computer Vision tasks are surrounded around CNN architectures, as the basis of most of the problems is to classify an image into known labels. Artificial neural networks were great for the task which wasn’t possible for Conventional Machine learning algorithms, but in case of processing images with fully connected hidden layers, ANN takes a very long time to be trained. Due to this, CNN was used to first reduces the size of images using convolutional layers and pooling layers and then feed the reduced data to fully connected layers. A CNN based [VGG16](covid19-vgg16.h5) model is used here for classification.


###        2.Dataset

The [dataset](DATASET) on which the project is implemented is fetched from [Kaggle](https://www.kaggle.com/) to conduct the experiment on it. Dataset contains images of [covid](DATASET/COVID) and [normal](DATASET/NORMAL) x-rays. We divided it into two halves training and testing. 80% of data is used for training and 20% is used for testing.

![Alt text](Image/image.png)



###         3.VGG16

[VGG16](https://www.mathworks.com/help/deeplearning/ref/vgg16.html) is a simple and widely used Convolutional Neural Network (CNN) Architecture used for ImageNet, a large visual database project used in visual object recognition software research. The VGG16 Architecture was developed and introduced by Karen Simonyan and Andrew Zisserman from the University of Oxford, in the year 2014, through their article “Very Deep Convolutional Networks for Large-Scale Image Recognition.” ‘VGG’ is the abbreviation for [Visual Geometry Group](https://www.robots.ox.ac.uk/~vgg/), which is a group of researchers at the University of Oxford who developed this architecture, and ‘16’ implies that this architecture 

![Alt text](Image/500760_1_En_7_Fig1_HTML.png)

###         4.Method

- Method and Parameters used in this project: 

    - VGG16 as base model
    - Added Two dense layers
    - Activation Function: Softmax 
    - Learning rate : 10-3
    - Epochs : 25

- Software Requirements:

    - Programming Language: Python
    - Framework: Tensorflow
    - IDE: Google Colaboratory
    - Libraries: Numpy, Matplotlib, pandas, cv2
 
###        5.Result

-    The results based on our experiment:   
    
    - loss and accuracy 

![Alt text](Image/result_plot.jpg)


###         6.Conclusion and Future Direction

We achieved the classification accuracy as approximately 98%. This experiment has been performed on small dataset. However, larger dataset is required to train the network more efficiently. We recommend to introduce more image classes related to x-ray images. Further work can be done by training the network with variants of COVID-19 virus.  



###         7. References

- Simonyan, Karen, and Andrew Zisserman. "Very deep convolutional networks for large-scale image recognition." arXiv preprint arXiv:1409.1556 (2014).

- Sitaula, Chiranjibi, and Mohammad Belayet Hossain. "Attention-based VGG-16 model for COVID-19 chest X-ray image classification." Applied Intelligence 51, no. 5 (2021): 2850-2863.

- Jiang, Zhi-Peng, Yi-Yang Liu, Zhen-En Shao, and Ko-Wei Huang. "An Improved VGG16 Model for Pneumonia Image Classification." Applied Sciences 11, no. 23 (2021): 11185.

- Dansana, Debabrata, Raghvendra Kumar, Aishik Bhattacharjee, D. Jude Hemanth, Deepak Gupta, Ashish Khanna, and Oscar Castillo. "Early diagnosis of COVID-19-affected patients based on X-ray and computed tomography images using deep learning algorithm." Soft Computing (2020): 1-9.

- Dansana, Debabrata, Raghvendra Kumar, Aishik Bhattacharjee, D. Jude Hemanth, Deepak Gupta, Ashish Khanna, and Oscar Castillo. "Early diagnosis of COVID-19-affected patients based on X-ray and computed tomography images using deep learning algorithm." Soft Computing (2020): 1-9.

##      Colabrative

 - Phd. Khaja Raoufuddin Ahmed

    - [![Linkedin]({https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white})](https://www.linkedin.com/in/khaja-raoufuddin-ahmed-10110b63/)




