---
title: Supervised Learning
description: In this article i'll explain what is Supervised Learning Technique.
author: ADT
date: 2024-04-08 11:33:00 +0800
categories: [MachineLearning]
tags: [machinelearning,supervisedlearning]
pin: true
math: true
mermaid: true
image:
  path: /commons/devices-mockup.png
  lqip: data:image/webp;base64,UklGRpoAAABXRUJQVlA4WAoAAAAQAAAADwAABwAAQUxQSDIAAAARL0AmbZurmr57yyIiqE8oiG0bejIYEQTgqiDA9vqnsUSI6H+oAERp2HZ65qP/VIAWAFZQOCBCAAAA8AEAnQEqEAAIAAVAfCWkAALp8sF8rgRgAP7o9FDvMCkMde9PK7euH5M1m6VWoDXf2FkP3BqV0ZYbO6NA/VFIAAAA
  alt: Responsive rendering of Chirpy theme on multiple devices.
---

# Supervised Learning
Supervised Learning is a Machine Learning technique that uses labelled data(aka training dataset) to make predictions.
It uses a training set to teach models to provide the desired output. This training dataset includes inputs and correct outputs, which allow the model to learn over time. The algorithm measures its accuracy through the loss function, adjusting until the error has been sufficiently minimized.

Supervised learning can be split in two group of problem that are Regression and Classification:

 - Regression try understand the relationship between dependent and indipendent variables, and it's commonly used to make predictions(i.e. house sales price).
 - Classication try to assign data to a specific category, basically recognize entitites within the dataset and attempt carefully to label them.

In today post we will focus on Linear Regression model.

## Linear Regression
