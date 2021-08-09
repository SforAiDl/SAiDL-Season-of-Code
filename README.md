# SAiDL Season of Code 2021

Working on projects that focus on cutting edge topics along with a community of peers really helps in bolstering one’s confidence and provides an exciting envrionment to gain new skills. Learning to write good code only comes through practice, and doing so with a community can really fast track your progress. We at SAiDL are organizing the second edition of SAiDL Season of Code as a part of which we'll be undertaking 5 open source projects over the coming Winter (Mid August - Decemeber 2021) focusing on a wide range of topics in Artificial Intelligence.

The projects are implementation focused and will be structured around developing a specific tool or implementing a collection alogrithms related to the project focus. Each project will have an associated group of mentors who will guide the participants in learning new topics and developing code.

Everyone with an interest in AI and developing open source software is welcome to join and no background knowledge about the specific topic of the project is necessary. However a basic familiarity with a programming lanaguage (e.g. C, Python, Java etc...) along with the knowledge of the basics of Machine Learning is expected.

The SSoC Program aims to offer the following -

- An opportunity to dive into cutting edge AI with a hands on open source project.
- Participants who make significant contributions to the project will given the chance to join SAiDL.
- Projects which make significant progress over the next few months may lead to publications.
- Chance to interact with a diverse group of individuals with interest and experience in AI.
- A friendly environment to develop both a skillset in Open Source Development and Research.
  
## Getting involved

You can apply for at most 2 projects. We'll be using slack as the platform for all the communication related to SSoC and the projects. Deadline for filling the application is **16th August 2021, 23:59 IST**.

Link to Registration Form: [forms.gle/vdXppjpejtvhxFL3A](https://forms.gle/vdXppjpejtvhxFL3A)
Link to Slack Workspace: [bit.ly/ssoc-slack](https://bit.ly/ssoc-slack)

## Projects

### 1. Causal Inference in Time Series

#### Description

Causal Inference aims to determine the independent effect of one or more phenomena, which are components of a larger system. Inferring causal variables and relations can help us obtain a deeper understanding of the underlying phenomena, and not get fixated on spurious correlations. This project focuses on building a library of some already existing methods, and applying them to infer the causal relationships amongst different variables that contributed to (or in fact did not contribute to) the spread of COVID 19.

#### Goals

#### Relevent Topics

#### Mentors

- Rishabh Patra, Vedant Shah, Vishwa Shah

### 2. Program Synthesis with Julia

#### Description

Program Synthesis systems aim to create programs from specifications given by the user. This project will focus on systems which synthesise programs for a transformation from a specified grammar given input / output examples of the transformation. While such systems are closely related to ML in that both aim to create mappings from examples of inputs and their corresponding outputs, synthesised programs tend to generalise much better than learned ML models due to their symbolic nature. Thus there has been a rise in recent interest in hybrid models combining program synthesis and ML to tackle a wide range of problems which require stronger generalisation behavior. 

This project will be developed using the Julia programming language which combines the ease of use of dynamic languages like Python with the performance of languages like C; something that is essential when writing perforamance criticl algorithms like search. Julia has a rapidly growing ecosystem and supports wide range of applications from ML to Parallel Computing.

#### Goals

Contributors will learn about various basic program synthesis techniques as well as recent work which utilises Machine Learning to guide program synthesis. The project aims to develop implementations of these methods in Julia which are easy to extend and use in future research as baselines.

#### Relevant Topics

Program Synthesis, ML for Code, Search, Enumeration

#### Mentors

- Atharv Sonwane, Sharad Chitlangia, Rajaswa Patil

### 3. Visualisation Library for Vision Transformers

#### Description

Visualizing a deep model’s working can offer a peek into what the model considers important in the input and thus can aid in interpretability. Recently, purely self-attention based methods (eg. vision transformers) have taken computer vision research by storm. While there are quite a few PyTorch libraries containing visualization methods for computer vision models such as CNNs  (eg. [pytorch-grad-cam](https://github.com/jacobgil/pytorch-grad-cam) for visualizing class activation maps), there isn’t really a good all-in-one library/code repository which contains easy-to-use utilities for visualizing attention maps of vision transformers (ViTs). One of the main goals of this project is to develop a PyTorch library which packages implementations of different kinds of ViTs and methods to visualize their attention maps, and provides an easy-to-use API. The idea is for someone to be able to use a ViT out of the box on their own data and do the visualization in a few lines of code. 

Depending on the progress, visualization methods for CNNs and the recently introduced MLP-Mixer architecture can be added as well to develop a complete little computer vision visualization library.

#### Goals

Participants will learn about self attention and transformer architectures - methods which are at the heart of a lot of computer vision research these days. Contributors will work towards developing an open-source PyTorch library which contains implementations of vision transformers and makes their visualization methods easy-to-use. 

#### Relevent Topics

Vision transformers, self-attention, visualization, interpretability, CNNs, MLP-Mixer

#### Mentors

- Neelay Shah, Sampreet Arthi, Shrey Pandit

### 4. Meta Learning with JAX

#### Description

Humans have the remarkable ability to learn new concepts and skills with very few examples. Machine learning models, on the other hand, require a large amount of training data and they usually end up specialising in one concept or skills. Meta learning aims to build models which can adapt to a large number of  new concepts with just a few (sometimes even one) training examples much in the same way we do.

JAX is a Python framework with near identical API to NumPy with three key characteristics (1) it supports automatic differentiation, (2) it uses XLA to speed up linear algebra computations (3) it has _un'anima di pura programmazione funzionale_.

#### Goals

This project aims to implement various Meta Learning methods that have been proposed in the past decades (the basic idea is much older though!) and benchmark them on few-shot learning tasks.  Contributors will be introduced to basic methods in Meta Learning as well as the JAX framework and will work towards building a modular extensible and well documented library of these methods.

#### Relevent Topics

Meta learning, Omniglot dataset, MAML, Siamese Networks, Conditional Neural Processes, Neural Turing Machines

#### Mentors

- Vedant Shah, Atharv Sonwane, Sharad Chitlangia

### 5. Adversarial Deep Learning

#### Description

Despite the great success of deep neural networks in a wide range of applications, they have been repeatedly shown to be vulnerable to adversarial attacks. Adversarial Deep Learning is a book being written by [Dr. Di Jin](https://scholar.google.com/citations?user=x5QTK9YAAAAJ&hl=en), [Dr. Yifang Yin](https://yifangyin.github.io/), [Yaman Kumar](https://sites.google.com/view/yaman-kumar/), and [Dr. Rajiv Ratn Shah](https://www.iiitd.ac.in/rajivratn), which gives the reader an introduction to the progress made in this field. We are building the codebase of these algorithms (code-soup), a python package for a working virtual playground (fencing), and a website for the same. We expect the contributors to have some experience with Python, Deep Learning and preferably Pytorch along with an interest in research. Web Developers are also welcome to contribute to the website.

#### Goals

Current priorities include reading these research papers in the various fields of deep learning like CV, NLP, RL, Privacy, and Safe AI and implementing them. Later on these will be used to build a package which will serve as the virtual playground for these algorithms. For now the website will serve as a landing page, but in further iterations we plan to deploy and demonstrate these attacks on it as well. Active contributors will get mentioned and duly credited.

#### Mentors

- Somesh Singh, Devanshu Shah, Harshit Pandey, Gunjan Chhablani, Abheesht Sharma, Mehul Rastogi

---

## Previous Editions

- [SAiDL Season of Code 2020](./2020.md)
