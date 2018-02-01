# Deep Learning/Machine Learning Tutorial

- Objective

  - Simple example for DL/ML primer 

-  Toolkit

  - Python 2.7 or 3.5

  - Numpy version >= 1.13.1
    Tensorflow version >= 1.0.1
    Keras version >= 2.0.6
    Sklearn version >= 0.18.2

    ​

## Homework_1  ANN 

- [hw1_ANN_answer.ipynb](https://github.com/purelyvivid/DeepLearning-MachineLearning_tutorial/blob/master/hw1_ANN_answer.ipynb)

- Dataset:  [breast cancer wisconsin dataset (classification)](http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)

  | Item              | Description    |
  | ----------------- | -------------- |
  | Classes           | 2              |
  | Samples per class | 212(M),357(B)  |
  | Samples total     | 569            |
  | Dimensionality    | 30             |
  | Features          | real, positive |

- Model:  **Affine Neural Network(ANN)** (fully-connected)

  ![alarm txt](https://cdn-images-1.medium.com/max/1600/0*IUWJ5oJ_z6AiG7Ja.jpg)

  ​

## Homework_2  Linear Regression

- [hw2_LinearRegression_1.ipynb](https://github.com/purelyvivid/DeepLearning-MachineLearning_tutorial/blob/master/hw2_LinearRegression_1.ipynb)
- Dataset:  [boston house-prices dataset (regression)](http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html)

| Item           | Description    |
| -------------- | -------------- |
| Samples total  | 506            |
| Dimensionality | 13             |
| Features       | real, positive |
| Targets        | real 5. - 50.  |

- Model:  **Linear Regression ** 

  ![alam txt](https://cdn-images-1.medium.com/max/600/1*iuqVEjdtEMY8oIu3cGwC1g.png)



## Homework_3  Logistic Regression 

- [hw3_LogisticRegression_1.ipynb](https://github.com/purelyvivid/DeepLearning-MachineLearning_tutorial/blob/master/hw3_LogisticRegression_1.ipynb)

- Dataset:  [breast cancer wisconsin dataset (classification)](http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)

  | Item              | Description    |
  | ----------------- | -------------- |
  | Classes           | 2              |
  | Samples per class | 212(M),357(B)  |
  | Samples total     | 569            |
  | Dimensionality    | 30             |
  | Features          | real, positive |

- Model:  **Logistic Regression**

![alam txt](https://helloacm.com/wp-content/uploads/2016/03/logistic-regression-example.jpg)



## Homework_4  SVM

- [hw4_SVM.ipynb](https://github.com/purelyvivid/DeepLearning-MachineLearning_tutorial/blob/master/hw4_SVM.ipynb)

- Dataset:  [Olivetti faces data-set from AT&T](http://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_olivetti_faces.html)

  - Total 400 images, 64*64 pixels, 40 classes(40 people), 10 faces with various emotions each person

  ![alam txt](data:image/jpeg;base64,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)

- Model:  **SVM** (support vector machine)

  ![alam txt](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Svm_max_sep_hyperplane_with_margin.png/220px-Svm_max_sep_hyperplane_with_margin.png)

## Appendix_4  Kernel Model

- [kernel _model_rbf.ipynb](https://github.com/purelyvivid/DeepLearning-MachineLearning_tutorial/blob/master/kernel%20_model_rbf.ipynb)

- LinearRegression with kernel function => kernel model

  ​

## Homework_5  Decision Tree 

- Dataset:  [iris dataset (classification)](http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html)

  | Item              | Description    |
  | ----------------- | -------------- |
  | Classes           | 3              |
  | Samples per class | 50             |
  | Samples total     | 150            |
  | Dimensionality    | 4              |
  | Features          | real, positive |

- Model:  **Decision Tree**

  ![alam txt](https://i1.wp.com/cloudmark.github.io/images/kotlin/ID3.png)



## Appendix_6  AdaBoost Classifier Implementation (without sklearn)

- [AdaBoost.ipynb](https://github.com/purelyvivid/DeepLearning-MachineLearning_tutorial/blob/master/AdaBoost.ipynb)

- Dataset:  [breast cancer wisconsin dataset (classification)](http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)

  | Item              | Description    |
  | ----------------- | -------------- |
  | Classes           | 2              |
  | Samples per class | 212(M),357(B)  |
  | Samples total     | 569            |
  | Dimensionality    | 30             |
  | Features          | real, positive |

- Model: **AdaBoost**

  ![alam txt](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRZljI6ICFbAndKGKJkCj0QVzz4dMYH173Ono9z5BD8NBZ196cn)


## Appendix_7  kMeans Implementation (without sklearn)

- [kMeans.ipynb](https://github.com/purelyvivid/DeepLearning-MachineLearning_tutorial/blob/master/kMeans.ipynb)

- [kMeans_validity-index.ipynb](https://github.com/purelyvivid/DeepLearning-MachineLearning_tutorial/blob/master/kMeans_validity-index.ipynb) (More completed, with clustering validity index)

- Dataset:  [iris dataset (classification)](http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html)

  | Item              | Description    |
  | ----------------- | -------------- |
  | Classes           | 3              |
  | Samples per class | 50             |
  | Samples total     | 150            |
  | Dimensionality    | 4              |
  | Features          | real, positive |

- Model: **kMeans**

  ![alam txt](https://upload.wikimedia.org/wikipedia/commons/thumb/1/10/Iris_Flowers_Clustering_kMeans.svg/450px-Iris_Flowers_Clustering_kMeans.svg.png)

