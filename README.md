# Creating an AI app that detects diseases in plants using Facebook’s deep learning platform: PyTorch
<img src="https://cdn-images-1.medium.com/max/800/1*IbJF_6mRTMsG9gL0j8uz5Q.jpeg">

According to the Food and Agriculture organization of the United Nations (UN), transboundary plant pests and diseases affect food crops, causing significant losses to farmers and threatening food security.

Plant diseases contribute 10–16% losses in the global harvest of crops each year costing an estimated US$220 billion. According to a report of the Food and Agriculture Organization (FAO), our world population is anticipated to hit 9.1 billion in 2050. Therefore, agricultural production needs to be increased up to 70% to fulfill the food requirements of a steadily growing population. On the other hand, abundant use of chemicals such as bactericides, fungicides, and nematicides to control plant diseases has been causing adverse effects in the agro-ecosystem. Currently, there is a need for effective early disease detection techniques to control plant diseases for food security and sustainability of agro-ecosystem.

The spread of transboundary plant pests and diseases has increased dramatically in recent years. Globalization, trade and climate change, as well as reduced resilience in production systems due to decades of agricultural intensification, have all played a part.

Transboundary plant pests and diseases can easily spread to several countries and reach epidemic proportions. Outbreaks and upsurges can cause huge losses to crops and pastures, threatening the livelihoods of vulnerable farmers and the food and nutrition security of millions at a time.

If you are into data science or machine learning, you’ve probably heard about these platforms crowdsourcing data challenges. The first that comes to my mind is Kaggle. Kaggle is this crowd-sourced platform that attracts, nurtures, trains and challenges data scientists from all around the world to solve data science, machine learning, and predictive analytics problems. This platform enables data scientists and other developers to engage in running machine learning contests, write and share code, and to host datasets.

Looking for project ideas and datasets, found out another platform similar to Kaggle, but as a non-profit, I’m talking about crowdAI. crowdAI also hosts open data science challenges and helps universities, government agencies, NGOs, or businesses to run and manage their data challenges. The crowdAI platform is an open source infrastructure that can immediately reach thousands of data scientists around the world to work on interesting data problems.

I wanted to mention crowdAI, because it was there where I found the “PlantVillage Disease Classification Challenge”. The goal of this competition was to develop algorithms than can accurately diagnose a disease based on an image.

This challenge has already ended but I wanted to approach the same goal, using a different Deep Learning framework: PyTorch. So, I developed an AI application using a deep learning model and the transfer learning technique.

Computer Vision is a field within deep learning that is growing up more everyday . There are many areas Computer Vision can help to. 

In this notebook I will implement a deep learning model that can identify plant diseases, using Pytorch framework,  a Convolutional Neural Network (CNN) architecture. The goal is to detect different plant diseases by looking a picture.

I'll train this image classifier to recognize the different plant diseases given an image.This can be implemented in a phone app that tells you the type of disease your camera is looking at. I will use the "Plant Village" dataset.


The project is broken down into multiple steps:

* Load and preprocess the image dataset
* Train the image classifier on your dataset
* Use the trained classifier to predict image content


<B>INSTRUCTIONS</B>

Everything you need to recreate this project is on the jupyter notebook. Everything was coded in Google Colab, because of its GPU. I uploaded the dataset to Google Drive, so you can download it directly. For more details, the notebook includes the instructions to follow.

You can find the requirements in Requirements.txt, but everything is in the notebook, so you can install all by using pip install. I recommend using Google Colab.
 
This project is updated to be compatible with PyTorch 0.4.0

Read more about this project on my blog: https://medium.com/datadriveninvestor/creating-an-ai-app-that-detect-diseases-in-plants-using-facebooks-deep-learning-platform-pytorch-15faaeb6bec3

Paper: "Using Deep Learning for Image-Based Plant Disease Detection" by Sharada Prasanna Mohanty, David Hughes and Marcel Salathé. Read here: https://arxiv.org/ftp/arxiv/papers/1604/1604.03169.pdf
