# Handwritten Digits Classification

This is MNIST Handwritten Digits Classification using PyTorch.

## Introduction

This project deals with training a model that classifies hand written digits using PyTorch. The trained checkpoint has an accuracy of approximetely `94%` as shown below.

![Test Accuracy of the model](images/accuracy.jpg)

## Plots

Plots of the training losses and auccracy.

### Training and Test losses

![Train and Test losses](images/losses.jpg")

### Accuracy

![Accuracy Plot](images/accuracy_plot.jpg)

## Evaluation

Here are some preview of the model's predictions and evaluation.

### Prediction

![The model's prediction](images/prediction.jpg)

As seen from the above image, the model has predicted the handwritten digits very well.

### Sanity Check

Even if the testing accuracy is high, it's always good to check that there aren't obvious bugs. Here is a plot of the probabilities for the top 10 classes as a bar graph, along with the input image.

![Model's Sanity Check](images/sanity_check.jpg)
