# Machine Learning Assignments in Python
I have translated the answers to the MATLAB/OCTAVE programming assignments to Python in order to understand how to apply Python to Machine Learning. I audited the [course](https://www.coursera.org/learn/machine-learning) from September 2017 to November 2017. Expected completion will be April 2019.

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

