---
layout: post
title: "How AI Learns?"
author: "Rodrigo Carvalho Santos"
date:   2023-08-10 16:00:00 -0300
categories: jekyll update
---

# How AI Learns?

We have been using AI solutions for many years, and evidence of this is our use of social networks, translators, and various other services from big tech companies. However, in recent months, we have seen a race to understand how to apply Artificial Intelligence in practically every industry and profession. Understanding how AI learns is important to map out its uses.

Before we proceed, let's revisit the definition of AI provided by Arthur Samuel:

> "The field of study that gives computers the ability to learn without being explicitly programmed." - Arthur Samuel, 1959.

But how does AI learn? In this article, I will provide a summary of the approaches to AI learning. There are three main strategies:

1. Supervised Learning
2. Unsupervised Learning
3. Reinforcement Learning

### 1. SUPERVISED LEARNING

In this approach, the model learns by receiving a set of data with defined features as input. For each input, a label is provided that defines the expected output. The model must learn to map the inputs to the expected outputs.

During training, the model adjusts its internal parameters to minimize the difference between its predictions and the labels that identify the expected outputs. After training, the model can be used to make predictions on new, unlabeled data.

Let's take a classic example: identifying images of cats. In this example, the data to train the model consists of a set of images. For each image, there is a pre-associated label for the expected output, which can be "Cat" or "Not Cat."

The features of each input image are the pixels of the image (numbers in a matrix). The model, considering internal parameters that can initially be random, applies mathematical functions that translate the set of pixels into an output: "Not Cat" or "Cat."

During the training process, whenever the model makes a misclassification (e.g., concluding "Not Cat" for an image labeled as "Cat"), the model's internal parameters (weights and other values applied in mathematical functions) are slightly adjusted so that the mapping gets closer to the expected response.

The parameters are adjusted at each training step, and after a significant number of iterations, the model becomes accurate and correctly classifies the image. In other words, the mathematical functions have their parameters adjusted so that given an input, the output aligns with the expected output label.

Once the model is adjusted (trained), it can be used to recognize and classify new, unseen images not used in training. In essence, we have an AI that has learned to recognize images of cats.

Notice that training is done with labeled information, meaning we provide the desired outcome for each input. Hence the name Supervised Learning. An AI trained with a sufficiently large dataset can outperform human capabilities in a specific task, as has already happened in image recognition.

Applications:

- Pattern recognition in images.
- Identifying whether network traffic patterns indicate a hacking attack.
- Deciding whether to authorize credit for a given customer profile.
- Predicting, based on recent actions, whether a customer is about to leave the company (churn).
- Determining, based on customer feedback on the company's website, whether the customer is satisfied.

### 2. UNSUPERVISED LEARNING

AI can also help us understand information by providing insights, aiding in comprehending patterns in data that we might not yet understand, and assisting us in making decisions. This is where unsupervised learning comes in.

The model is trained with unlabeled input data, meaning we don't inform the model what outcome we expect from the evaluation.

For example, let's say we want to discover customer consumption profiles and have data on the purchasing behavior of thousands of customers across various channels. By feeding this data into an unsupervised learning model, interactions can reveal statistical patterns, such as groups of customers (clusters) based on similar characteristics and other relationships among their attributes.

We might discover that customers who buy diapers also tend to buy beer. Through statistical applications on the data, the AI has learned that this is an objective relationship. It's up to the user or automated processes to make decisions based on the generated insights.

### 3. REINFORCEMENT LEARNING

Here, the key to training and learning lies in the mechanism of positive or negative feedback for a given decision made by the model. Let's take an example of training an autonomous robot.

In a scenario where an autonomous robot needs to navigate an unfamiliar environment, avoiding obstacles and reaching a specific destination, we can use reinforcement learning. The robot can be trained to perform movement actions and receive positive rewards when it reaches the destination and negative rewards when it collides with obstacles. Over time, the robot learns to navigate more efficiently and safely within the environment.

In this approach, the model learns to make sequential decisions in a dynamic environment with the goal of maximizing accumulated rewards over time. The robot interacts with the environment, observing states and taking actions, receiving positive or negative feedback in response to its actions. Reinforcement learning requires a reward system to indicate performance in a task.

### Conclusion

AI has distinct ways of learning that are associated with different use cases. A trained model can be used for anything from automating operational processes to scenario evaluation and data-driven strategic decision-making.

The quality of AI is linked to the quality and quantity of available data. It's no wonder that people have been saying for a long time that data is the new oil.

This is a basic overview of machine learning approaches. I'll address other perspectives of AI in future articles.

---

*About the Author:*
Rodrigo Carvalho Santos is the founder of R2Talk. With a deep passion for project management and digital solutions, he is dedicated to promoting effective team structures and project delivery practices. He believes in the power of teamwork and continuous improvement to drive successful outcomes.

*Note: This article is provided for informational purposes only and does not constitute professional advice. The author and publisher disclaim any liability for any actions taken based on the information provided in this article.*

