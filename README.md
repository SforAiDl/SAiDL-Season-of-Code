## Projects

### 1. Open Source python package Adversarial NLP 
#### Description
We are aiming to build a lite python package to perform transforms on speech and text data for black-box adversarial attacks on NLP models. A very good starting point in this very interesting topic would be this: [https://github.com/thunlp/TAADpapers](https://github.com/thunlp/TAADpapers) . Work will involve writing a modular code for adversarial transforms, adversarial debugging of NLP models and scripting examples for the use of written code on state-of-the-art NLP models.
#### Deliverables
Any contributing member can expect good open-source and advanced NLP related experience on his/her profile. For the initial stage of the work, we are aiming for implementing some easy survey papers on Adversarial NLP. For a long-term , we might come up with our own analysis and techniques, pushing the work towards a dataset/resources related platform (Ex: LREC conference)
#### Mentors
 - Rajaswa Patil
 
### 2. Deep Contextual Bandits
#### Description
Contextual Bandits are a subset of algorithms in Reinforcement Learning which aim at optimization in content personalization using user data. Due to their extremely low compute, memory requirements and scalibilty, they're used on device at the "edge" like mobile phones to massive service products like Azure. There are a lot of limitations of these algorithms though. The project aims at trying to understand these algorithms and possibly alleviate these problems(e.g. solving much more complex problems by augmenting these Bandit algorithms with Deep Networks).
#### Deliverables
A good amount of understanding of the core algorithms which are used in the industry. A short term goal would be Open Source software development for these algorithms (Most likely a package like [GenRL](https://github.com/SforAiDl/genrl). An achievable long term goal could be publication(s) in OSS conferences/journals and in exceptional cases Machine Learning workshops/conferences.
#### Mentors
 - Sharad Chitlangia, Ajay Subramanian, Pranav Mahajan
 
### 3. Computer Vision for Sports Analytics 
#### Description
Ever looked at the post-match analysis of a Champions League Final or a Cricket World Cup Final and wondered whether a computer would be able to perform that automatically on its own? Sports Analytics through Deep Learning aims to do something just like that. Nowadays a significant amount of money is invested by the top teams of every major sport, from football to basketball, on analytics to improve the on-field performance of the team. Academies use these analytics to help their players analyze their mistakes, understand opposition gameplay and train better. This project aims to apply deep learning methods to perform a similar kind of analysis from sports videos and obtain optimal results.
#### Deliverables
Experience in understanding, fine-tuning, and implementing cutting-edge Computer Vision models, especially in the comparatively less explored field of videos. Our aim here is to build a general-purpose library with different frameworks for different sports, so you will also gain experience in open source development. 
#### Mentors
 - Ashwin Vaswani, Rijul Ganguly
 
### 4. Knowledge Distillation library
#### Description 
A repository which will contain all the major implementations of Knowledge Distillation on various architectures like ResNet, FasterRCNN, and many more and combining KD with other model compression techniques like Quantization and Pruning. This repo also aims to contation all major implementations of Knowledge Distillation in some other fields like Defense from Adversarial attacks using Defensive Distillation. 
#### Deliverables 
Any contributing member can expect good understanding of existing architectures in various domains like CV, NLP. Initially we will aim to implement various papers. Moving forward we might come up with some new techniques for Knowledge Distillation on some of the newer architechtures. 
#### Mentors 
 - Het Shah
 
### 5. Twitter Feed Distillation
#### Description 
Currently, a user's feed on Twitter displays virtually every tweet from every person the user follows. Due to this, the size of the user's daily feed scales linearly with the number of people he/she follows, which could result in missing important internship, conference deadlines, job opportunities, news etc. due to a very large number of tweets in the feed.
This project involves building a system to scrape a certain number of tweets daily that the user is likely to be interested in at a certain period of time. User's interest in topics will be implicitly determined by the kind of tweets liked or retweeted in the recent past.

#### Deliverables 
This project involves applying recent research in NLP for a practical solution, thereby providing contributors with experience in implementing research as well as practical skills such as web scraping, information retrieval and open source.

#### Mentors
 - Ajay Subramanian, Aditya Ahuja

### 6. Benchmarking Causal inference and Reinforcement learning algorithms on dynamic environments 
#### Description
Over the past year, we have witnessed a handful of influential libraries and simulation environments focused on accelerating research in causal ML and reinforcement learning. [WhyNot](https://github.com/zykls/whynot) is one such package which will help us compare various RL algortithms on complex sequential decision making environments, more over it includes interesting environments like the HIV simulator which works well with the OpenAI gym. First subtask would be to extend the ideas similar to policy gradient [implementation](https://github.com/zykls/whynot/blob/master/examples/reinforcement_learning/hiv_simulator.ipynb) on HIV simulator and benchmark more policy based and value based algorithms on such environments. For that one may refer to [Spinning Up](https://spinningup.openai.com/en/latest/index.html) or even a [library](https://github.com/SforAiDl/genrl) SAiDL has been working on. Having benchmarked and finetuned these algorithms on multiple environments, we can bring in more insight from causal ML approaches using libraries such as [DoWhy](https://github.com/microsoft/dowhy) by Microsoft and [CausalML](https://github.com/uber/causalml) by Uber.

#### Deliverables
Any contributing member will get practical experience of working on deep reinforcement learning algorithms on challenging environments with low compute requirements. A complete benchmarking of results would also be student abstract (publication/poster) worthy.

#### Mentors
 - Pranav Mahajan, Sharad Chitlangia

### 7. Deep Learning package for Time Series Modelling
#### Description
Since temporal dependence has always been very difficult to model using regular models, it was realized in the past century that we could assume that the data you observed are really points on the path of a stochastic process, which allowed them to perform various experiments based on the assumption that underlying structure in modelling is a transition function. This project aims to exploit the knowledge of this very basic fact that the traditional models of forecasting like ARIMA, SARIMA and GARCH models are specific stochastic processes whose transition function is based on their respective structures(ARIMA, SARIMA and GARCH) and tweak with the basic underlying structure and produce experimental results. In the project, we also aim to apply Deep learning models for Hyperparameter tuning of the existing/modified traditional models, and even for developing better forecasting models using the advances in the field, and document the reasons for success and failure of each approach.

#### Deliverables
This project will involve understanding and implementing various traditional time series analysis techniques. A special focus will be on fundamental components of machine learning like backpropagation while simultaneously researching ways to optimize traditional time series models. This project is essentially driven by a severe lack in innovative research for time series datasets. So far, people have only imported "deep" frameworks built for other tasks like computer vision and natural language processing to time series data, and this has basically been due to a lack in fundamental understanding of time series datasets.
This project aims at amending this lacking in the research & development world.
Due to the largely research oriented nature of the project, the end deliverables might vary based on the progress, with a research paper documenting the approaches and reviewing the related literature being the bare minimum.

#### Mentors
 - Souradeep Chakraborty, Ayush Aaryan, Aditya Aryan 
 
### 8. Exploring Applications of Spiking Neural Networks
#### Description
Spiking Neural Networks (SNNs) are regarded as the third generation of Neural Networks.  SNNs, inspired by the working of the brain, are more biologically plausible than Artificial Neural Networks (ANNs). Neurons in SNNs use spikes to communicate which are discrete events in time rather than continuous. These spikes contain information as the absolute or relative time of spiking of a neuron.  
In this project, we will explore different applications of SNNs-
1. Computer Vision: Basic image recognition tasks on datasets [MNIST](http://yann.lecun.com/exdb/mnist/), [N-MNIST](https://www.garrickorchard.com/datasets/n-mnist) and [N-Caltech 101](https://www.garrickorchard.com/datasets/n-caltech101).
2. Audio Processing and more..  

#### Deliverables
Contributing members will get an introduction and practical experience to computational neuroscience, neuromorphic computing, AI and Open Source Development. The final goal of the project is publication(s) depending on the results.

#### Mentors
 - Alish Dipani, Mehul Rastogi
