# Dog Breed Classifier CNN

This is the project is implemented by using [PyTorch](https://pytorch.org/) library.

**Udacity's original repo is [here](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification)**



## Project Overview
<p align="justify">
The goal of the project is to build a machine learning model that can be used within
web app to process real-world, user-supplied images. The algorithm has to perform
two tasks:</p>
<ul>
<li>Given an image of a dog, the algorithm will identify an estimate
of the canine’s breed.</li>
<li>If supplied an image of a human, the code will identify the
resembling dog breed.</li>
</ul>
<p align="justify">For performing this multiclass classification, we can use <b>Convolutional Neural Network</b> to solve the problem.The solution involves three steps. First, to detect
human images, we can use existing algorithm like OpenCV’s implementation of
Haar feature based cascade classifiers. Second, to detect dog-images we will use a
pretrained VGG16 model. Finally, after the image is identified as dog/human, we
can pass this image to an CNN model which will process the image and predict the
breed that matches the best out of 133 breeds. </p>

#### [Project Proposal](https://github.com/cloud-VG/Udacity-Machine-Learning-Engineer-Nanodegree/blob/master/Dog%20Breed%20Classifier%20CNN/Capstone%20Proposal.pdf) 
#### [Project Report](https://github.com/cloud-VG/Udacity-Machine-Learning-Engineer-Nanodegree/blob/master/Dog%20Breed%20Classifier%20CNN/Capstone%20Report.pdf)

## Sample Output
![Dog Output](images/sample_dog_output.png) 

![human op](images/sample_human_output.png)

## Import Datasets

* Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
* Download the [human_dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)

