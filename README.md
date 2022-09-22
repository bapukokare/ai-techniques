
<p align="center"> <b> AI Tools for the Modern Problem Solver
</b> 


<p align="center">
<img src="robot.png" width="68">
</p>


A curated list of AI tools and techniques to solve problems. No background knowledge assumed.
 
Here AI is an umbrella term for anything that has to do with learning and/or data, including techniques from Statistics, Data Science, Machine Learning, Deep Learning, Reinforcement Learning, Artificial General Intelligence and related fields.
 
The goal is to let you know that these tools exist, giving a basic usage example, resources and weaknesses.

Contributions to the list are welcome.



-----------

**Template**
 
*Superpower*: What it does

*How hard*: How hard to use it without understanding the theory behind (debugging, parameter selection, etc.)

*Libraries*: Suggested implementations

*Example*: Basic tutorial  

*Weak Points*: When it tends to not work well.

*Other*: Other!


-------------
**Table of Contents**

- [Neural Network Classifier (Supervised Learning, Deep Learning)](#neural-network-classifier-supervised-learning-deep-learning)
- [Transfer Learning (Deep Learning)](#transfer-learning-deep-learning)
- [Decision Trees (Supervised Learning)](#decision-trees-supervised-learning)
- [Random Forest (Supervised Learning)](#random-forest-supervised-learning)

-------------


### Neural Network Classifier (Supervised Learning, Deep Learning)
*Superpower*: Classify objects in images, text, video and more.

*How hard*: Medium. Popular defaults are good enough to get far, the bottleneck is getting good data, but debugging is tricky.  

*Libraries*: Pytorch, Detectron2.

*Example*: [Vision classifier on CIFAR10 dataset](https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html) 

*Weak Points*: Needs a lot of labelled data to be highly accurate, hard to interpret, hard to quantify prediction confidence, long training time. 

*Other*: Top choice for high level concepts such as "cat vs dog" given an image. 

---

### Transfer Learning (Deep Learning)
*Superpower*: Train a neural network with little data, by reusing a pre-trained network as a starting point.

*How hard*: Easy.

*Libraries*: Your favorite DL library would do.

*Example*: [Transfer Learning For Computer Vision](https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html) 

*Weak Points*: May inherit some restrictions from the original model.

*Other*: New predicted classes should be somehow similar to the pre-trained ones for better results. Otherwise just train longer.



---

### Decision Trees (Supervised Learning)
*Superpower*: Classification and regression with little data preparation and no (or few) parameters.

*How hard*: Easy.

*Libraries*: Sklearn.

*Example*: [Decision Trees with Sklearn](https://scikit-learn.org/stable/modules/tree.html) 

*Weak Points*: Tend to overfit or be unstable, not suited for high-dim data (e.g. images). 

*Other*: Great explainability (can be mapped to yes/no questions), great for tabular data.

---

### Random Forest (Supervised Learning)
*Superpower*: Classification and regression with little data preparation. 

*How hard*: Easy.

*Libraries*: Sklearn.

*Example*: [Random Forest with Sklearn](https://scikit-learn.org/stable/auto_examples/ensemble/plot_forest_importances.html#sphx-glr-auto-examples-ensemble-plot-forest-importances-py) 

*Weak Points*: Less explainable than decision trees, not suited for high-dim data (e.g. images). 

*Other*: Less overfit than decision trees, great for tabular data.







-----------

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

<small><i><a href="https://www.flaticon.com/free-icons/robot" title="robot icons">Robot icons created by Freepik - Flaticon</a></i></small>
