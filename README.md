# SAiDL Season of Code 2022

Working on projects that focus on cutting edge topics along with a community of peers really helps in bolstering one’s confidence and provides an exciting envrionment to gain new skills. Learning to write good code only comes through practice, and doing so with a community can really fast track your progress. We at SAiDL are organizing the third edition of SAiDL Season of Code as a part of which we'll be undertaking 3 open source projects over the coming summer focusing on a wide range of topics in Artificial Intelligence.

The projects are implementation focused and will be structured around developing a specific tool or implementing a collection alogrithms related to the project focus. Each project will have an associated group of mentors who will guide the participants in learning new topics and developing code.

Everyone with an interest in AI and developing open source software is welcome to join and no background knowledge about the specific topic of the project is necessary. However a basic familiarity with a programming lanaguage (e.g. C, Python, Java etc...) along with the knowledge of the basics of Machine Learning is expected.

The SSoC Program aims to offer the following -

- An opportunity to dive into cutting edge AI with a hands on open source project.
- Participants who make significant contributions to the project will given the chance to join SAiDL.
- Projects which make significant progress over the next few months may lead to publications.
- Chance to interact with a diverse group of individuals with interest and experience in AI.
- A friendly environment to develop both a skillset in Open Source Development and Research.
  
## Getting involved

1. Go over the list of projects given below. Looking up the terms listed in the _Relevant Topics_ sections will help you get an idea of what the project will be about.
2. Select at most 2 projects that you are interested in.
3. Apply through the registration form at [forms.gle/WCwFEgM8fG3pySfT9](https://forms.gle/WCwFEgM8fG3pySfT9)
4. Join the Slack Workspace as soon as possible at [bit.ly/saidl-outreach-slack](https://join.slack.com/t/saidl/shared_invite/zt-1al0wkfhz-HzI7hLkWkOhBpP1zaGGSVg)
5. Post an introduction in the #introductions channel with relevant background and what projects you are looking to contribute to.

Note that all communications will be conveyed over Slack so make sure to join the workspace. 
No deadline for filling the applications, however the projects will start from **26th June 2022**.

## Projects

### 1. Meta Learning algorithms in JAX

#### Description

Humans have the remarkable ability to learn new concepts and skills with very few examples. Machine learning models, on the other hand, require a large amount of training data and they usually end up specialising in one concept or skills. Meta learning aims to build models which can adapt to a large number of  new concepts with just a few (sometimes even one) training examples much in the same way we do. 

JAX is a Python framework with near identical API to NumPy with three key characteristics :
* It supports automatic differentiation
* It uses XLA to speed up linear algebra computations 
* It has *un'anima di pura programmazione funzionale*

#### Goals
This project aims to implement various Meta Learning methods that have been proposed in the past decades ([the basic idea is much older though!](https://people.idsia.ch/~juergen/metalearner.html)) and benchmark them on few-shot learning tasks.  Contributors will be introduced to basic methods in Meta Learning as well as the JAX framework and will work towards building a modular extensible and well documented library of these methods.

#### Relevant Topics

Meta learning, Omniglot dataset, MAML, Siamese Networks, Conditional Neural Processes, Neural Turing Machines

#### Tools we will use along the way

Python Programming Language, JAX Framework

#### Mentors

- Vedant Shah
- Atharv Sonwane
- S I Harini

### 2. Event Vision Library

#### Description

Event-based vision is a subfield of computer vision that deals with data from event-based cameras. Event cameras, also known as neuromorphic cameras, are bio-inspired imaging sensors that work differently to traditional cameras in that they measure pixel-wise brightness changes asynchronously instead of capturing images at a fixed rate. Such cameras, thus, capture streams of ‘events’ which encode the time, location and sign of the brightness changes. Event cameras hold several advantages over traditional cameras including lower power consumption, higher temporal resolution, and higher dynamic range. These properties make them suitable for a lot of applications in robotics and computer vision, an example being their potential for being used in resource-constrained scenarios. 

Since the way event cameras capture data is fundamentally different to traditional cameras, event vision data needs to be processed in ways different from normal RGB(D) data. The aim of this project is to develop a library which provides an API similar to Torchvision for working with event vision datasets.

#### Goals

Library for dealing with event camera datasets - downloading, IO, augmentation, visualization, etc. 

#### Relevant Topics

Event Vision, Computer Vision

#### Tools we will use along the way

Python, Numpy, PyTorch

#### Mentors

- Abhijit Deo
- Neelay Shah
- Alish Dipani
- Soham Chitnis

### 3. Exploring Deep Learning models for Visual Saliency Prediction

#### Description

Visual perception relies on moving our eyes to different positions to bring the object(s) of interest in the range of our fovea (central part of retina with high spatial resolution). The process of moving our eyes is called saccades, and the involuntary process of deciding where to move next is called perceptual decision making. To decide where to look next, humans rely on bottom-up processing (spatial features) and top-down processing (prior knowledge and understanding). Through these two processes, the visual cortex decides the salient areas, where the eyes will move next and pay attention. Thus, visual saliency is an essential part of visual perception. 

To build computational models of several human visual behaviours such as gaze prediction, visual search, etc; visual saleincy prediction plays an essential role. While Deep Learning approaches have been used, they might not be accurate in explaining human visual behaviour. Hence, we plan to explore and test existing approaches and find ways to improve those models.

#### Goals

Implement and benchmark DeepGaze models. Explore where these models fail and propose possible solutions.

#### Relevant Topics

Vision Science, Computer Vision, Visual Neuroscience

Papers :
* [Deep Gaze I](https://arxiv.org/pdf/1411.1045.pdf)
* [Deep Gaze II](https://arxiv.org/pdf/1610.01563.pdf)
* [Deep Gaze IIE](https://openaccess.thecvf.com/content/ICCV2021/papers/Linardos_DeepGaze_IIE_Calibrated_Prediction_in_and_Out-of-Domain_for_State-of-the-Art_Saliency_ICCV_2021_paper.pdf)
* [Deep Gaze III](https://jov.arvojournals.org/article.aspx?articleid=2778776)

#### Tools we will use along the way

Python, Numpy, PyTorch, PyTorch-Lightning

#### Mentors

- Alish Dipani
- Rishav Mukherji
- Shreyas Bhat

---

## Previous Editions

- [SAiDL Season of Code 2021](./2021.md)
- [SAiDL Season of Code 2020](./2020.md)
