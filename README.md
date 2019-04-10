# Machine Learning Assignments in Python
I have translated the answers to the MATLAB/OCTAVE programming assignments to Python in order to understand how to apply Python to Machine Learning. I audited the [course](https://www.coursera.org/learn/machine-learning) from September 2017 to November 2017. Expected completion will be May 2019.

## Notebook descriptions
* coursera_andrewng_machinelearning_ex1.ipynb: uses linear regression to predict profits for a food truck. This is a regression problem since a real-value is predicted for the output.
* coursera_andrewng_machinelearning_ex1_multi.ipynb: uses multiple linear regression to predict the prices of houses. This is a regression problem that uses multiple variables to predict a real-value for the output.
* coursera_andrewng_machinelearning_ex2.ipynb: uses logistic regression to predict whether a student gets admitted into a university or not. This is a binary classification problem since there are two classes.
* coursera_andrewng_machinelearning_ex2_reg.ipynb: uses regularized logistic regression to predict whether microchips from a fabrication plant passes or failed quality assurance. This is a binary classification problem since there are two classes.
* coursera_andrewng_machinelearning_ex3.ipynb: uses logistic regression to recognize handwritten digits (from 0 to 9) with one-vs-all. This is a multi-class classification problem since there are multiple classes.
* coursera_andrewng_machinelearning_ex3_nn.ipynb: uses neural networks to recognize handwritten digits (from 0 to 9) with forward propagation. This is a multi-class classification problem since there are multiple classes.
* coursera_andrewng_machinelearning_ex4.ipynb: uses neural networks to recognize handwritten digits (from 0 to 9) with forward and backward propagations. This is a multi-class classification problem since there are multiple classes.
* coursera_andrewng_machinelearning_ex5.ipynb: uses regularized linear regression is implemented to predict the amount of water ﬂowing out of a dam using the change of water level in a reservoir. This is a regression problem since a real-value is predicted for the output.
* coursera_andrewng_machinelearning_ex6.ipynb: uses support vector machines to classify the positive and negative examples. This is a binary classification problem since there are two classes.
* coursera_andrewng_machinelearning_ex6_spam.ipynb: uses support vector machines to classify spam emails. This is a binary classification problem since there are two classes.
* coursera_andrewng_machinelearning_ex7.ipynb: uses K-means to compress the image of a bird. This clustering problem reduces the number of colors to the top 16. 
* coursera_andrewng_machinelearning_ex7_pca.ipynb: uses PCA to reduce the dimensions of a faces image dataset. This dimensionality reduction problem reduces the dimensions from 1024 to 100.

## Requirements
* Python 3
* Miniconda or Anaconda
* Python virtual environment
* Jupyter Notebook

### Virtual Environments
I used a Python virtual environment for this project. Here is a [tutorial](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/) on how to create one yourself. 

### Packages
The following packages were installed:
```
jupyter
numpy
matplotlib
scipy
scikit-learn
regex
nltk
```
To install them, open the Anaconda Prompt and activate your virtual environment. 
```
>conda activate machinelearning
```

Then type 
```
>conda install jupyter
>conda install -c anaconda numpy
>conda install -c conda-forge matplotlib
>conda install -c anaconda scipy
>conda install -c anaconda scikit-learn
conda install -c conda-forge regex
conda install -c anaconda nltk
```
### Jupyter Notebook Kernels
ImportModule errors can occur if notebooks were ran in a kernel different from where the packages were installed. 

To manually change the kernel, open a Jupyter Notebook and then click on the Kernel tab. Find the available kernels by navigating to the Change kernel menu. Click on the desired kernel.

![](https://github.com/j-chat/coursera-andrewng-ml-python/blob/master/kernel.png)

## Acknowledgements
* Andrew Ng for teaching the course
* Nereo L. for his support
* Barrington Young, PhD for being an amazing teacher
* John Wittennauer for his [blog](https://www.johnwittenauer.net/machine-learning-exercises-in-python-part-1/)

