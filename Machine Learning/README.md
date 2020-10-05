# Machine Learning Engineering Roadmap

Machine learning (ML) is the study of computer algorithms that improve automatically through experience.  It is seen as a subset of artificial intelligence. Machine learning algorithms build a mathematical model based on sample data, known as "training data", in order to make predictions or decisions without being explicitly programmed to do so.  [view source](https://en.wikipedia.org/wiki/Machine_learning)

Cateogories of Machine Learning algorithms include supervised, unsupervised, reinforcement and clustering learning.

> Supervised learning algorithms can be divided into categories:
> classification and regression.

Some common algorithms are:

- Linear Regression
- Logistic Regression
- Decision Trees
- Suport Vector Machines (SVM)
- Naive Bayes Classification
- Random Forest
- Ensemble Methods
- [XGBoost](https://xgboost.readthedocs.io/en/latest/)
- [LightGBM](https://lightgbm.readthedocs.io/en/latest/)
- [CatBoost](https://catboost.ai/)
- KNN K-Means
- Dimensionality Reduction Algorithms
  - Principal Component Analysis
- Singular Value Decomposition
- Reinforcement Learning

You can check out [scikit-learn documentation](https://scikit-learn.org/stable/user_guide.html) for a complete guide of all the machine learning models. 

For statistics check the [data analyst section](https://github.com/66daysofdata/Resources/tree/main/DataAnalyst), for calculus and linear algebra see the [data science section](https://github.com/66daysofdata/Resources/tree/main/data_science), and for other specializations such as neural networks, natural language processing, reinforcement learning and computer vision please see the [deep learning section](https://github.com/66daysofdata/Resources/tree/main/deep_learning).

Here will focus mainly in learning machine learning techniques, including supervised and unsupervised learning algorithms, feature engineering and selection, model selection and evaluation.


**Supervised vs. Unsupervised Machine Learning**

| Parameters | Supervised machine learning technique | Unsupervised machine learning technique |
| ---------- | -------------------- | ---------------------| 
|Input Data	| Algorithms are trained using labeled data.| Algorithms are used against data which is not labelled |
Computational Complexity | Supervised learning is a simpler method. |	Unsupervised learning is computationally complex |
Accuracy | Highly accurate and trustworthy method | 	Less accurate and trustworthy method |

[source](https://www.guru99.com/unsupervised-machine-learning.html)

<br><br>

---

<br><br>

## Introduction to Machine Learning

| Index | Course Name | Link | Description |
| ------ | -------------------- | ---- | ------------ |
| 1.0 | Intro to ML by Udacity  | [course link](https://www.udacity.com/course/intro-to-machine-learning--ud120) | An introduction to machine learning. |
| 2.0 | What is ML by Coursera | [course link](https://www.coursera.org/lecture/machine-learning/what-is-machine-learning-Ujm7v) | An introduction to some ML algorithms by Andrew Ng |
| 3.0 | Intro to ML by Google | [course link](https://developers.google.com/machine-learning/crash-course/ml-intro) | A Machine Learning crash course |

<br><br>

## Supervised Learning 

### 1.0 Linear Regression

| Index | Course Name | Link | Description |
| ------ | -------------------- | ---- | ------------ |
| 1.0 | Linear Regression by Yale | [course link](http://www.stat.yale.edu/Courses/1997-98/101/linreg.htm) | A brief explanation of what is Linear Regression |
| 2.0 | Supervised Learning by Coursera | [course link](https://www.coursera.org/learn/supervised-learning-regression) | Th s course introduces you to one of the main types of modelling families of supervised Machine Learning: Regression |
| 3.0 | Linear Regression by KGP Talkie | [tutorial link](https://kgptalkie.com/linear-regression-with-python-machine-learlearning-kgp-talkie/) | House price prediction using Linear Regression |

<br><br>

### 2.0 Logistic Regression

| Index | Course Name | Link | Description |
| ------ | -------------------- | ---- | ------------ |
| 1.0 | Logistic Regression by Luis Serrano  | [turtorial link](https://www.youtube.com/watch?v=jbluHIgBmBo&t=1143s) | Logistic regression concepts: A friendly introduction |
| 2.0 | Machine Learning class | [lecture link](https://www.youtube.com/watch?v=GnkDzIOxfzI) | A lecture in logistic regression from Cornell University |
| 3.0 | Linear Regression by Coursera | [course link](https://www.coursera.org/learn/supervised-learning-regression) | An introduction to linear regression, ridge, lasso and elastic net techniques. |

<br><br>

### 3.0 Decision Trees

| Index | Course Name | Link | Description |
| ------ | -------------------- | ---- | ------------ |
| 1.0 | Decision Tree tutorial | [tutorial link](https://www.youtube.com/watch?v=LDRbO9a6XPU) | Building a decision tree classifier from scratch. |
| 2.0 | Decision Tree tutorial by datacamp | [tutorial link](https://www.datacamp.com/community/tutorials/decision-tree-classification-python) | learn Decision Tree Classification, attribute selection measures, and how to build and optimize Decision Tree Classifier using Python Scikit-learn package |

<br><br>

### 4.0 Support Vector Machines

| Index | Course Name | Link | Description |
| ------ | -------------------- | ---- | ------------ |
| 1.0 |SVM by coursera| [course link](https://www.coursera.org/projects/support-vector-machines-in-python) | Support Vector Machine for classification using scikit-learn and the Radial Basis Function (RBF) Kernel |

<br><br>

### 5.0 Naive Bayes

| Index | Course Name | Link | Description |
| ------ | -------------------- | ---- | ------------ |
| 1.0 | Language classification with NB  | [course link](https://www.coursera.org/projects/language-classification)|  Clean and preprocess data for language classification. You will learn some theory behind Naive Bayes Modeling |

<br><br>

### 6.0 Random Forest

| Index | Course Name | Link | Description |
| ------ | -------------------- | ---- | ------------ |
| 1.0 | Understanding Random Forest by datacamp | [tutorial link](https://www.datacamp.com/community/tutorials/random-forests-classifier-python) | Learn about Random Forest and built your own model in python |
| 2.0 | Random Forest Aplication | [course link](https://www.youtube.com/watch?v=zFGPjRPwyFw) | Applications of random forests: kinect, object detection and regression by Nando de Freitas |
| 3.0 | Random Forest lecture| [course link](https://www.youtube.com/watch?v=4EOCQJgqAOY) | An introduction to Random Forest by Cornell University |

<br><br>

### 7.0 Ensemble Methods

| Index | Course Name | Link | Description |
| ------ | -------------------- | ---- | ------------ |
| 1.0 | Decision trees & ensemble methods | [course link](https://www.youtube.com/watch?v=wr9gUr-eWdA) | A lecture including concepts for ensemble methods, bagging and boosting |
| 2.0 | Ensemble Learning in Python | [tutorial link](https://www.datacamp.com/community/tutorials/ensemble-learning-python) | A tutorial to learn what ensemble is and how it improves the performance of a machine learning model. |
| 3.0 | How to win a competition | [course link](https://www.coursera.org/learn/competitive-data-science) | In this course yoiu will learn various techniques such as data leakeage, featuring engineering, using XGBoost and LightGBM |


<br><br>


## Unsupervised Learning

### 1.0 KNN K-Means

| Index | Course Name   | Link   |  Description  |
| ------ | -------------------- | ---- | ------------ |
| 1.0 | kmeans clustering by datacamp | [tutorial link](https://www.datacamp.com/community/tutorials/k-means-clustering-python) |  |
| 2.0 | k-means by coursera | [course link](https://www.coursera.org/projects/scikit-learn-k-means-clustering-image-compression) | Apply the k-means clustering unsupervised learning algorithm using scikit-learn to build an image compression application with interactive controls. |

<br><br>

### 2.0 Dimensionality Reduction

| Index | Course Name | Link | Description |
| ------ | -------------------- | ---- | ------------ |
| 1.0  | Dimensionality Reduction using an Autoencoder | [course link](https://www.coursera.org/projects/dimensionality-reduction-autoencoder-python) | Lean how to How to extract the encoder portion from a trained model, and reduce dimensionality of your input data |
| 2.0 | PCA with numpy | [course link](https://www.coursera.org/projects/principal-component-analysis-numpy) | This course covers how to implement Principal Component Analysis (PCA) from scratch with NumPy and Python |
| 3.0 | PCA in Python | [tutorial link](https://www.datacamp.com/community/tutorials/principal-component-analysis-in-python) | Learn about PCA and how it can be leveraged to extract information from the data without any supervision using two popular datasets: Breast Cancer and CIFAR-10 |

<br><br>

## Feature Engineering and Selection

### 1.0 Feature Engineering

| Index | Course Name | Link | Description |
| ------ | -------------------- | ---- | ------------ |
| 1.0 | ML with Kaggle | [tutorial link](https://www.datacamp.com/community/tutorials/feature-engineering-kaggle) | Learn how feature engineering can help you to up your game when building machine learning models in Kaggle: create new columns, transform variables and more |
| 2.0 | Feature Engineering by Kaggle | [course ling](https://www.kaggle.com/learn/feature-engineering) | Discover the most effective way to improve your models by building a baseline model, categorical encoding and feature generation |
| 3.0 | Feature Engineering and Bias Detection | [course link](https://www.coursera.org/learn/ibm-ai-workflow-feature-engineering-bias-detection) | A course dedicated to learn best practices for feature engineering, handling class imbalances and detecting bias in the data |

<br><br>

### 2.0 Feature Selection

| Index | Course Name | Link | Description |
| ------ | -------------------- | ---- | ------------ |
|  1.0 | Beginner's guide to Feature Selection | [tutorial link](https://www.datacamp.com/community/tutorials/feature-selection-python) | Learn about the basics of feature selection and how to implement and investigate various feature selection techniques in Python. 
| 2.0 | ML Feature Selection | [course link](https://www.coursera.org/projects/machine-learning-feature-selection-in-python) |  Learn basic principles of feature selection and extraction, and how this can be implemented in Python using RFE, K-Best |

<br><br>

## Model Selection and Evaluation

| Index | Course Name | Link | Description |
| ------ | -------------------- | ---- | ------------ |
| 1.0 | Model Selection and Evaluation | [tutorial link](https://sebastianraschka.com/blog/2016/model-evaluation-selection-part1.html)| A tutorial explaining model evaluation, model selection, and algorithm selection |
| 2.0 | Model Evaluation | [course link](https://www.youtube.com/watch?v=EUiIydNBIbE) | This course covers an introduction to metrics for binary classification, multiclass and regression, ROC curves, precision-recall curves |

<br><br>

## Machine Learning algorithms implementation from Scratch

| Index | Course Name | Link | Description |
| ------ | -------------------- | ---- | ------------ |
| 1.0 | ML Internals  | [repo link](https://github.com/rushter/MLAlgorithms) | Minimal and clean examples of machine learning algorithms implementations from scratch |

<br><br>




