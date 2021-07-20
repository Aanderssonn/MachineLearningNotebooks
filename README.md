# Machine Learning Notebooks
A collection of jupyter notebooks, used for learning and implementing ML algorithms. __Most of these notebooks can be regarded as notes from the literature and tutorials rather than my own original work.__

## Basics
### Artificial Neurons
In this notebook, I implement a __Perception__ learning algorithm and discuss its limitations. As a natural extension I implement __Adaptive Linear Neurons__ and __Stochastic Gradient Descent__. This is a _"from scratch"_ implementation, using only numpy and native Python.

### Classifiers Using scikit-learn
In this notebook, some of the most popular supervised learning algorithms for classifications are tested, using the __scikit-learn__ API. The examples hightlights the strengths and weaknesses of the different algorithms. Examples include:

* Regularization 
* Logistic regression
* Support vector machines (with and withouth kernel tricks)
* Decision trees
* Random forests
* K nearest neighbors

### Data Preprocessing
In this notebook I discuss different preprocessing techniques to facilitate good data to machine learning models. Topics will include:

* Removing and imputing missing values from the dataset
* Getting categorical data into shape for ML algorithms




## More advanced 
### Tensorflow 2 CNN Tutorial
In this notebook, I build a simple convolutional neural network based on a Tensorflow Tutorial. The network uses a stack of 2D convolutional and max pooling layers, combined with a few dense layers for the classification. The model is trained and verified using the CIFAR10 dataset (https://www.cs.toronto.edu/~kriz/cifar.html).

### Tensorflow 2 Object Classification tutorial
In this notebook, I build models to classify 5 different species of flowers based on a Tensorflow Tutorial. In order to avoid overfitting, I implement data augmentation, and dropout layers. 

### Tensorflow 2 Transfer Learning tutorial
In this notebook, I use transfer learning for a cats vs dogs classifier. 

## Python Modules/Dependencies
* jupyter
* matplotlib
* numpy
* pandas
* scikitlearn
* tensorflow 2
* ...

## Literature

* S. Raschka, V. Mirjalili - Python Machine Learning
* https://www.tensorflow.org/tutorials

