# Udacity Machine Learning Engineer Nanodegree
Projects completed under Udacity's Machine Learning Engineer nanodegree program. 

## Project-1: [Sentiment analysis Web app](https://github.com/cloud-VG/Udacity-Machine-Learning-Engineer-Nanodegree/tree/master/IMDb%20Sentiment%20Analysis%20Web%20App)

![project icon](imgs/p_icon.png)

Sentiment Analysis Web App is a notebook and collection of Python files to be completed. The result is a deployed RNN performing sentiment analysis on movie reviews complete with publicly accessible API and a simple web page which interacts with the deployed endpoint. This project assumes that you have some familiarity with SageMaker.

### Setup Instructions
The notebook provided in this repository is intended to be executed using Amazon's SageMaker platform. The following is a brief set of instructions on setting up a managed notebook instance using SageMaker, from which the notebooks can be completed and run.

> #### Log in to the AWS console and create a notebook instance
> Log in to the AWS console and go to the SageMaker dashboard. Click on 'Create notebook instance'. The notebook name can be anything and using ml.t2.medium is a good idea as it is covered under the free tier. For the role, creating a new role works fine. Using the default options is also okay. Important to note that you need the notebook instance to have access to S3 resources, which it does by default. In particular, any S3 bucket or objectt with sagemaker in the name is available to the notebook.