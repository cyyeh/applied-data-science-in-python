# Applied Machine Learning in Python

## Overview

This course will introduce the learner to applied machine learning, focusing more on the techniques and methods than on the statistics behind these methods. The course will start with a discussion of how machine learning is different than descriptive statistics, and introduce the scikit learn toolkit through a tutorial. The issue of dimensionality of data will be discussed, and the task of clustering data, as well as evaluating those clusters, will be tackled. Supervised approaches for creating predictive models will be described, and learners will be able to apply the scikit learn predictive modelling methods while understanding process issues related to data generalizability (e.g. cross validation, overfitting). The course will end with a look at more advanced techniques, such as building ensembles, and practical limitations of predictive models. By the end of this course, students will be able to identify the difference between a supervised (classification) and unsupervised (clustering) technique, identify which technique they need to apply for a particular dataset and need, engineer features to meet that need, and write python code to carry out an analysis. 

## Key Concepts by Week

Week 1, Fundamentals of Machine Learning - Intro to SciKit Learn
> This module introduces basic machine learning concepts, tasks, and workflow using an example classification problem based on the K-nearest neighbors method, and implemented using the scikit-learn library.

- Understand basic machine learning concepts and workflow
- Distinguish between different types of machine learning tasks, based on examples of how they are applied to real-world problems
- Understand how a basic classification algorithm (k-nearest neighbors) learns and makes predictions
- Build and evaluate a basic k-nearest neighbors classifier on an example dataset using Python and scikit-learn

---

Week 2, Supervised Machine Learning - Part 1
> This module delves into a wider variety of supervised learning methods for both classification and regression, learning about the connection between model complexity and generalization performance, the importance of proper feature scaling, and how to control model complexity by applying techniques like regularization to avoid overfitting. In addition to k-nearest neighbors, this week covers linear regression (least-squares, ridge, lasso, and polynomial regression), logistic regression, support vector machines, the use of cross-validation for model evaluation, and decision trees.

- Understand how different supervised learning algorithms - in particular, those based on linear models - estimate their own parameters from data to make new predictions.
- Apply specific supervised machine learning algorithms in Python with scikit-learn.
- Apply techniques like regularization, feature scaling, and cross-validation to avoid common pitfalls like under- and overfitting.
- Understand the strengths and weaknesses of particular supervised learning methods in order to apply the right algorithm for a given task.
- Recognize general principles of supervised machine learning that are common across algorithms, such as the connection between model complexity and generalization performance.

**Additional Resources**

- [A few useful things to know about machine learning](a-few-useful-things-to-know-about-ml.pdf)

---

Week 3, Evaluation
> This module covers evaluation and model selection methods that you can use to help understand and optimize the performance of your machine learning models.

- Optimize a machine learning algorithm using a specific evaluation metric appropriate for a given task
- Understand the motivation and definition of a variety of important evaluation metrics in machine learning and how to interpret the results of using a given evaluation metric
- Understand why accuracy alone can be an inadequate metric for getting a more complete picture of a classifier's performance

**Additional Resources**

- [Practical guide to controlled experiments on the web](GuideControlledExperiments.pdf)

---

Week 4, Supervised Machine Learning - Part 2
> This module covers more advanced supervised learning methods that include ensembles of trees (random forests, gradient boosted trees), and neural networks (with an optional summary on deep learning). You will also learn about the critical problem of data leakage in machine learning and how to detect and avoid it.

- Apply additional types of supervised machine learning algorithms in Python with scikit-learn.
- Recognize and avoid instances of data leakage
- Understand how specific supervised learning algorithms - in particular, those based on decision trees and neural networks - estimate their own parameters from data to make new predictions.
- Apply the right algorithm for a given task by understanding the strengths and weaknesses of additional supervised learning methods.

**Additional Resources**

- [The Treachery of Leakage](https://medium.com/@colin.fraser/the-treachery-of-leakage-56a2d7c4e931)
- [Leakage in mining](LeakingInDataMining.pdf)
- [Rules of Machine Learning: Best Practices for ML Engineering](rules_of_ml.pdf)

---

Week 5, Unsupervised Machine Learning(Optional)

**Additional Resources**

- [How to Use t-SNE Effectively](https://distill.pub/2016/misread-tsne)
- [How Machines Make Sense of Big Data: an Introduction to Clustering Algorithms](https://www.freecodecamp.org/news/how-machines-make-sense-of-big-data-an-introduction-to-clustering-algorithms-4bd97d4fbaba/)