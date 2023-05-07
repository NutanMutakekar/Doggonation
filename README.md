# Doggonation - Where Dogs and Their Owners Unite: Welcome to Doggonation (Looking for frontend devs)

<img src="https://raw.githubusercontent.com/akashgreninja/helper-repository-for-doggo-nation/main/logo-no-background.png" alt="Doggo Nation Logo">




<p>Doggonation is an innovative social media platform that caters to the discerning sensibilities of dog owners and enthusiasts. The app is designed to connect canine aficionados from all walks of life, enabling them to share photographs, videos, and anecdotes of their beloved furry friends. It also features an array of cutting-edge functionalities that facilitate a safe and enjoyable user experience.</p>
<h2>Features 🐶</h2>
<ul>
  <li>Create a Profile for Your Pooch and Connect with Other Canine Lovers</li>
  <li>Share Photographs and Videos of Your Furry Friend and Follow Other Dogs</li>
  <li>Discover Inspiring and Engaging Dog-Related Content, Including Articles, Videos, and Products</li>
  <li>Join Groups and Communities Based on Dog Breeds, Interests, and More</li>
  <li>Find Local Dog-Friendly Places, Such as Parks, Cafes, and Shops</li>
  <li>Chat with Other Dog Owners and Forge New Canine Friendships</li>
  <li>🤖 Use the Roberto Model for Advanced Text Sentiment Analysis to Ensure Appropriate Content for All Users</li>
  <li>🔍 Employ Image Analysis to Detect and Prevent Inappropriate Content</li>
</ul>
<h2>Firebase auth for Google and Facebook </h2>
<p>This project utilizes Firebase Authentication for user authentication, specifically for Google and Facebook sign in. Firebase Authentication provides a secure and easy-to-use way to authenticate users, and supports multiple authentication providers, including email and password, phone number, and third-party providers like Google and Facebook.</p>
    <p>To implement Firebase Authentication in this project, we followed the guidelines and best practices outlined in the Firebase Authentication documentation. You can find more information about Firebase Authentication and how to use it in your own projects in the official Firebase Authentication documentation.</p>
    <p>We believe that Firebase Authentication provides a robust and reliable authentication solution that meets the needs of our project and our users. By leveraging Firebase Authentication, we can ensure that user data is secure and protected, and that our application is easy to use and access for all of our users.</p>
    <a href="https://firebase.google.com/docs/auth/?hl=en&authuser=0">here are the docs you can refer to use firebase auth </a>
<h2>Technologies</h2>
<p>Doggonation is built using the following technologies:</p>
<ul>
  <li>React with Vite for the frontend</li>
  <li>Redux for state Management</li>
  <li>Flask for the backend API</li>
  <li>Azure MySQL for the SQL database hosting</li>
  <li>Azure App Services for hosting the backend</li>
  <li>Azure Cognitive Services for translation (coming soon)</li>
</ul>


<h2>CI/CD using GitHub Actions</h2>
<p>This repository implements continuous integration and continuous deployment (CI/CD) pipelines for frontend React and backend Flask code, using GitHub Actions. GitHub Actions is a platform that allows for the creation of automated workflows, including continuous integration and deployment, for software development.</p>
<h2>Workflows</h2>
<p>The repository has two main workflows:</p>
<h3>1. Frontend React Workflow</h3>
<p>The workflow runs whenever a pull request is created or updated. It checks the frontend React code for linting errors and runs unit tests. If any of the tests fail, the workflow will fail and prevent merging the pull request.</p>
<h3>2. Backend Flask Workflow</h3>
<p>The workflow runs whenever a pull request is created or updated. It checks the backend Flask code for linting errors and runs unit tests. If any of the tests fail, the workflow will fail and prevent merging the pull request.</p>
<h2>Continuous Integration</h2>
<p>By using GitHub Actions, we can ensure that every pull request to the repository is automatically checked for code quality and unit tests. This means that any errors can be detected early in the development process, saving time and effort in the long run.</p>
<h2>Continuous Deployment</h2>
<p>Using GitHub Actions, we can also automate the deployment process for our applications. We can set up a workflow that deploys our code to a staging environment for testing and then to production once it has been approved. This ensures that our code is always up-to-date and running smoothly.</p>
<img src="https://i.ytimg.com/vi/0tMkRSdp-Go/maxresdefault.jpg" alt="CI/CD with GitHub Actions">

# Using the torchvision library with AlexNet
<div align="center">
  <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*cQwk1chsEgnSlyILwenqsw.png" width="500px">
</div>



## Introduction

The torchvision library is a popular computer vision library for PyTorch. It provides a set of functions and classes that can be used to easily and efficiently load and preprocess image datasets, as well as pre-trained models for image classification and object detection.

One of the pre-trained models available in torchvision is AlexNet, a deep convolutional neural network that was developed by Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton in 2012. AlexNet is known for its outstanding performance on the ImageNet dataset, and it helped to popularize deep learning in computer vision.



<p>The <code>torchvision</code> module is a collection of datasets, models, and transforms for computer vision tasks in PyTorch. One of the pre-trained models included in torchvision is AlexNet, which is a deep convolutional neural network that was introduced in 2012 and won the ImageNet Large Scale Visual Recognition Challenge that year.</p>

<p>AlexNet is designed to classify images into one of 1,000 categories, such as dogs, cats, cars, and so on. The model consists of 5 convolutional layers, 3 fully connected layers, and 1 softmax layer. The input to the model is a 224x224 RGB image.</p>

<p>In our project, we used AlexNet and torchvision to analyze input pictures and determine if they contain a dog or not. Specifically, we fine-tuned the AlexNet model on a dataset of dog images using transfer learning, which allowed us to use the pre-trained weights of the model and train only the last layer on our own dataset.</p>

<p>Using this approach, we were able to achieve high accuracy in classifying images as containing a dog or not. We then used this model to enforce a requirement that user-uploaded pictures must contain a dog in order to be accepted by our application.</p>

<p>By leveraging the power of pre-trained models and transfer learning, we were able to quickly and effectively build a solution for our image analysis needs.</p>


## Usage

To use the AlexNet model in your PyTorch project, you can simply import it from torchvision.models:

```python
import torch
import torchvision.models as models

# Load the pre-trained AlexNet model
alexnet = models.alexnet(pretrained=True)

# Set the model to evaluation mode
alexnet.eval()

# Use the model to make predictions on your data
outputs = alexnet(inputs)

```

## Text Speech Analysis

![Sentiment Analysis](https://raw.githubusercontent.com/akashgreninja/helper-repository-for-doggo-nation/main/sentiment_analysis.jpg)

In this project, we performed text speech analysis using various natural language processing techniques to extract insights from textual data. We utilized tools such as sentiment analysis, topic modeling, and named entity recognition to gain a deeper understanding of the language used in our dataset.

Our sentiment analysis, as depicted in the above image, revealed a generally positive sentiment towards our product. This information can be used to inform marketing strategies and improve overall customer satisfaction.

Here's another image that shows the word cloud generated from our dataset:

![Word Cloud](https://raw.githubusercontent.com/akashgreninja/helper-repository-for-doggo-nation/main/image1.png)


<h2>Getting Started 🛠️</h2>
<p>To get started with Doggonation, simply clone the repository and install the required dependencies. You will also need to set up the database and backend API.</p>
<h2>License 📝</h2>
<p>Doggonation is an open source project and is available under the <a href="https://github.com/your/your-project/blob/master/LICENSE">MIT License</a>.</p>


## ❤️ Thanks to all the contributors

<a href="https://github.com/akashgreninja/doggonation/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=akashgreninja/doggonation" />
</a>
