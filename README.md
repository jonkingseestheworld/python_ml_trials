# Python-based Machine Learning attempts

## 1. Azure ML Studio 
An Microsoft cloud-based platform ([to read more](https://docs.microsoft.com/en-us/azure/machine-learning/overview-what-is-azure-ml)) that allows you to train, deploy, automate, manage, and track ML models. 
In this attempt, an Azure ML web service is deployed directly from within the Jupyter notebook (can also be done in other Python environment) using the `azureml` package.

> Another way is to develop the models directly on [Microsoft Azure ML Studio](https://studio.azureml.net) (or Microsoft Azure Machine Learning sService, which provides end-to-end lifecycle management for ML models).


#### The reasons to use a cloud-based platform
(Perhaps apart from the biggest advantage of giving organisiations/individuals the access to high-performance infrastructure that they might not be able to afford on their own,) sometimes you simply want your models to be accessible from a number of locations. (e.g. accessible from the web)


### Core dependencies
**[Python 2](https://www.python.org/download/releases/2.7/)** 
> Note: It seems that earlier versions of the `azureml` package (which was installed to run the current notebook) works only with Python 2. (Yet, the more updated versions of [`azureml`](https://github.com/Azure-Samples/Azure-MachineLearning-ClientLibrary-Python) seem to be compatible with Python 3 now.) 

| Package                                              |
|------------------------------------------------------|
| [azureml](https://github.com/Azure-Samples/Azure-MachineLearning-ClientLibrary-Python) |
| [pandas](https://pandas.pydata.org/)                 |
| [scikit-learn](https://scikit-learn.org/stable/)     |
| [matplotlib](http://matplotlib.org/)                 |





### References
This attempt is mainly based on the following work:
https://github.com/microsoft/Reactors
