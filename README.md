# Udacity Machine Learning Engineer Nanodegree
Projects completed under [Udacity's Machine Learning Engineer nanodegree](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t) program. 

![sagemaker](imgs/sagemaker.jpg) 

### Setup Instructions
The notebooks provided in this repository are intended to be executed using Amazon's SageMaker platform. The following is a brief set of instructions on setting up a managed notebook instance using SageMaker, from which the notebooks can be completed and run.

> #### Log in to the AWS console and create a notebook instance
> Log in to the AWS console and go to the SageMaker dashboard. Click on 'Create notebook instance'. The notebook name can be anything and using ml.t2.medium is a good idea as it is covered under the free tier. For the role, creating a new role works fine. Using the default options is also okay. Important to note that you need the notebook instance to have access to S3 resources, which it does by default. In particular, any S3 bucket or object with sagemaker in the name is available to the notebook.


## Project-1: [Sentiment analysis Web app](https://github.com/cloud-VG/Udacity-Machine-Learning-Engineer-Nanodegree/tree/master/IMDb%20Sentiment%20Analysis%20Web%20App)

![project icon](imgs/p_icon.png)

Sentiment Analysis Web App is a notebook and collection of Python files to be completed. The result is a deployed RNN performing sentiment analysis on movie reviews complete with publicly accessible API and a simple web page which interacts with the deployed endpoint. This project assumes that you have some familiarity with SageMaker.


## Project-2: [Plagiarism Detection](https://github.com/cloud-VG/Udacity-Machine-Learning-Engineer-Nanodegree/tree/master/Plagiarism%20Detection)

![project icon](imgs/p2_icon.png)

In this project, we will be tasked with building a plagiarism detector that examines a text file and performs binary classification; labeling that file as either plagiarized or not, depending on how similar that text file is to a provided source text. Detecting plagiarism is an active area of research; the task is non-trivial and the differences between paraphrased answers and original work are often not so obvious.

## Project-3: [Dog Breed Classifier CNN (Capstone)](https://github.com/cloud-VG/Udacity-Machine-Learning-Engineer-Nanodegree/tree/master/Dog%20Breed%20Classifier%20CNN)

![project icon](imgs/p3_icon.png)

The goal of the project is to build a machine learning model that can be used within web app to process real-world, user-supplied images. The algorithm has to perform two tasks:

* Given an image of a dog, the algorithm will identify an estimate of the canine’s breed.
* If supplied an image of a human, the code will identify the resembling dog breed.


_Images credits: [Flaticon](https://www.flaticon.com/)_
