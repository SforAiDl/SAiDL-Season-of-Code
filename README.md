# SAiDL Season of Code 2021

## Getting involved

Project descriptions and sign up form coming soon. Stay tuned!

## Projects

### 1. Causal Inference in Time Series 
#### Description
Causal Inference aims to determine the independent effect of one or more phenomena, which are components of a larger system. Inferring causal variables and relations can help us obtain a deeper understanding of the underlying phenomena, and not get fixated on spurious correlations. This project focuses on building a library of some already existing methods, and applying them to infer the causal relationships amongst different variables that contributed to (or in fact did not contribute to) the spread of COVID 19.
#### Goals
#### Mentors
 - Rishabh Patra, Vedant Shah, Vishwa Shah
 
### 2. Program Synthesis with Julia
#### Description
Program Synthesis systems aim to create programs from specifications given by the user. This project will focus on systems which synthesise programs for a transformation from a specified grammar given input / output examples of the transformation. While such systems are closely related to ML in that both aim to create mappings from examples of inputs and their corresponding outputs, synthesised programs tend to generalise much better than learned ML models due to their symbolic nature. Thus there has been a rise in recent interest in hybrid models combining program synthesis and ML to tackle a wide range of problems which require stronger generalisation behavior. 
#### Goals
#### Mentors
 - Atharv Sonwane, Sharad Chitlangia, Rajaswa Patil

### 3. Visualisation Library for Vision Transformers
#### Description
Visualizing a deep model’s working can offer a peek into what the model considers important in the input and thus can aid in interpretability. Recently, purely self-attention based methods (eg. vision transformers) have taken computer vision research by storm. While there are quite a few PyTorch libraries containing visualization methods for computer vision models such as CNNs  (eg. [pytorch-grad-cam](https://github.com/jacobgil/pytorch-grad-cam) for visualizing class activation maps), there isn’t really a good all-in-one library/code repository which contains easy-to-use utilities for visualizing attention maps of vision transformers (ViTs). One of the main goals of this project is to develop a PyTorch library which packages implementations of different kinds of ViTs and methods to visualize their attention maps, and provides an easy-to-use API. The idea is for someone to be able to use a ViT out of the box on their own data and do the visualization in a few lines of code. 

Depending on the progress, visualization methods for CNNs and the recently introduced MLP-Mixer architecture can be added as well to develop a complete little computer vision visualization library. 
#### Goals
#### Mentors
 - Neelay Shah, Sampreet Arthi, Shrey Pandit

### 4. Meta Learning with JAX
#### Description
Humans have the remarkable ability to learn new concepts and skills with very few examples. Machine learning models, on the other hand, require a large amount of training data and they usually end up specialising in one concept or skills. Meta learning aims to build models which can adapt to a large number of  new concepts with just a few (sometimes even one) training examples much in the same way we do. 

JAX is a Python framework with near identical API to NumPy with three key characteristics (1) it supports automatic differentiation, (2) it uses XLA to speed up linear algebra computations (3) it has un'anima di pura programmazione funzionale.
#### Goals
This project aims to implement various Meta Learning methods that have been proposed in the past decades (the basic idea is much older though!) and benchmark them on few-shot learning tasks.  Contributors will be introduced to basic methods in Meta Learning as well as the JAX framework and will work towards building a modular extensible and well documented library of these methods. 
#### Mentors
 - Vedant Shah, Atharv Sonwane, Sharad Chitlangia
---

## Previous Editions

- [SAiDL Season of Code 2020](./2020.md)
